문서 객체 모델 : 자바스크립트를 이용하여 웹 문서에 접근하고 제어할 수 있도록 객체를 사용해 웹 문서를 체계적으로 정리하는 방법

<HTML의 요소 관계 알아보기>
```
<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
	<title>DOM Tree 알아보기</title>
</head>
<body>
	<h1>Do it!</h1>
	<img src="images/doit.jpg" alt="공부하는 이미지">
</body>
</html>
```

DOM을 구성하는 기본 원칙
1. 모든 HTML 태그는 요소(element)노드임
2. HTML 태그에서 사용하는 텍스트 내용은 자식 노드인 텍스트(text>노드임
3. HTML 태그에 있는 속성은 자식 노드인 속성(attribute)노드임
4. 주석은 주석(comment) 노드임

getElementById(id) : id명으로 접근함
getElementsByClassName(class) : 클래스명으로 접근하며 여러 요소가 배열 형태로 저장됨
getElementsByTagName(tag) : 태그명으로 접근하며 여러 요소가 배열 형태로 저장됨
querySelector() : id명이나 선택자를 사용해 접근함
querySelectorAll() : 클래스명이나 태그명의 선택자를 사용해 접근함. 여러 노드가 노드 리스트 형태로 저장됨

<innerText, innerHTML 프로퍼티 사용하기>
```
<button onclick="inntext()">innerText로 표시하기</button>
<button onclick="innhtml()">innerHTML로 표시하기</button>
<h1>현재 시각: </h1>
<div id="current"></div>

<script>
	var now = new Date();
	
	function inntext(){
		document.getElementById("current").innerText = now;
	}
	function innhtml(){
		document.getElementById("current").innerHTML = "<em>" + now + "</em>";
	}
</script>
```

속성 가져오기 및 수정하기
getAttribute(속성) //태그에서 사용한 속성값을 가져옴
setAttribute(속성, 값) //태그의 속성을 특정한 값으로 지정함

<이미지 속성 가져오기>
```
	<div id="prod-pic">
		<img src="images/coffee-pink.jpg" alt="에디오피아 게뎀" id="cu[" width="200" height="200" onclick="displatSrc()">
	</div>

<script>
	function displaySrc(){
		var cup = document.querySelector("#cup");
		alert("이미지 소스: " + cup.getAttribute("src"));
	}
</script>
```
이벤트 처리하기
요소.addEventLustener(이벤트, 함수, 캡처 여부)

텍스트 노드를 사용하는 새로운 요소 추가하기
createElement() : 새로운 요소 노드를 만듦
createTextNode() : 새로운 텍스트 노드를 만듦
appendChild() : 텍스트 노드를 요소 노드의 자식으로 연결함
appendChild() : 요소 노드를 DOM에 연결함

속성값이 있는 새로운 요소 추가하기
createElement() : 새로운 요소 노드를 추가함
createAttribute() : 새로운 속성 노드를 추가함
속성값 지정하기 : 속성값을 프로퍼티로 지정
setAttributeNode() : 속성 노드를 요소 노드의 자식으로 연결
appendChild() : 요소 노드를 DOM에 연결

노드 삭제 
부모노드.removeChild(자식 노드)
 
