# self-study
대상

1. html 사용자에게 게시판을 구현한다.
2. 이를 로컬 스토리지를 활용한다.
3. 읽기, 수정, 삭제.
4. 활용기술

HTML
1. CSS
2. 자바스크립트

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<style>
    td, th{border:solid 1px;}
    table {
        border-collapse:collapse;
        }
</style>
</head>
<body>
    <table style="width:100%;border:solid 1px;">
        <tr>
          <th>No</th>
          <th>Title</th>
          <th>Whiter</th>
        </tr>
        <tr>
          <td>Jill</td>
          <td>Smith</td>
          <td>50</td>
        </tr>
        <tr>
          <td>Eve</td>
          <td>Jackson</td>
          <td>94</td>
        </tr>
      </table>

<h4 style="color:red">This is a Heading</h1>
<p style="color:blue">This is a paragraph.</p>
<a href="javascript:movew3school()">This is a link</a>
<br/>
<br/>
<br/>
<form method="post" action="view.html">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname">
    <input type="submit" value="전송">
  </form>
<img src="https://cdn.pixabay.com/photo/2021/08/06/18/46/dog-6526980_960_720.jpg" alt="W3Schools.com" width="104" height="142">
<p>
    This paragraph<br/>
    contains a lot of lines<br/>
    in the source code,<br/>
    but the browser<br/>
    ignores it.<br/>
    </p>
    
    <p>
    This paragraph<br/>
    contains         a lot of spaces<br/>
    in the source         code,<br/>
    but the        browser<br/>
    ignores it.<br/>
    </p>
   
    
</body>
<script>
    function movew3school () {
        window.location.href = "https://www.w3schools.com";
    }
</script>
</html>



<h1>2-3</h1>
<h2 style="color:#0000FF;">태그를 사용해서 웹 브라우저에 나타내기</h2>

<h3>제목</h3>
<p>텍스트 단락</p>
<table>
  <tr>
    <td>쉘1</td>
    <td>쉘2</td>
  </tr>
  <tr>
    <td>쉘3</td>
    <td>쉘4</td>
  </tr>
  </table>
 
 <h2 style="color:#000FFF;">시맨틱 태그를 사용하여 만든 웹 문서</h2>
 
 <div id="container">
  <header>
    <div id="logo">
      <a href="#"><h1>Dream Jeju</h1></a>
    </div>
    <nav>
      <ul id="topMenu">
        <li><a href="#">단체 여행</a></li>
        <li><a href="#">맞춤 여행</a></li>
        <li><a href="#">갤러리</a></li>
        <li><a href="#">문의하기</a></li>
      </ul>
    </nav>
  </header>
  <main class="contents">
    <section id="headling">
      <h3>몸과 마음이 치유되는 섬</h3>
    </section>
    <section id="activity">
      <h3>다양한 액티비티가 기다리는 섬</h3>
    </section>
  </main>
  <footer>
    <section id="bottomMenu">
      <ul>
        <li><a href="#">회사 소개</a></li>
        <li><a href="#">개인정보처리방침</a></li>
        <li><a href="#">여행 약관</a></li>
        <li><a href="#">사이트맵</a></li>
      </ul>
    </section>
  </footer>
  </div>
 
 <h1>2-4</h1>
 <h2>제목 텍스트 삽입하기</h2>

 <h3>레드향</h3>
 <h4>레드향 샐러드 레시피</h4>
 <h4>상품 구성</h4>
 
<h2><p>태그로 텍스트 단락 만들기</h2>
 
  <h3>레드향</h3>
  <p>껍질에 붉은 빛이 돌아 레드향이라 불린다.</p>
  <p>레드향은 한라봉과 귤을 교배한 것으로 <br> 일반 귤보다 2~3배 크고, 과육이 붉고 통통하다.</p>
  <p>비타민 C와 비타민 P가 풍부해<br> 혈액순환, 감기예방 등에 좋은 것으로 알려져 있다.</p>
     
<h2>인용문 태그 사용하기</h2>

  <h3>레드향</h3>
  <p>껍질에 붉은 빛이 돌아 레드향이라 불린다.</p>
  <p>레드향은 한라봉과 귤을 교배한 것으로 <br> 일반 귤보다 2~3배 크고, 과육이 붉고 통통하다.</p>
  <blockquote>
  비타민 C와 비타민 P가 풍부해<br> 혈액순환, 감기예방 등에 좋은 것으로 알려져 있다.
  </blockquote>
 
<h2>텍스트를 굵게 표시하기 <strong>,<b> 태그</h2>
경고나 주의 사항처럼 중요한 내용을 강조해야 할 때는 <strong>태그를 키워드처럼 단순히 글자만 굵게 표시할 때는 <b> 태그를 사용한다.
  
  <h3>레드향</h3>
  <p>껍질에 붉은 빛이 <b> 레드향 </b>이라 불린다.</p>
  <p>레드향은 한라봉과 귤을 교배한 것으로 <br> 일반 귤보다 2~3배 크고, 과육이 붉고 통통하다.</p>
  <p>비타민 C와 비타민 P가 풍부해<br> <strong>혈액순환, 감기예방</strong>등에 좋은 것으로 알려져 있다.</p>
  

  <h2>텍스트 기울여서 쓰기</h2>
  em태그에서 em은 강조를 뜻하고 i태그에서는 기울기체를 뜻한다. 
    em태그는 문장에서 흐름상 특정 부분을 강조하고 싶을 때 사용하고, i태그는 마음속의 생각이나 용어, 관용구 등에 사용한다. 

     
<h2>다양한 텍스트 관련 태그</h2>
  abbr : 줄임말을 표시하고 title속성을 함께 사용할 수 있음<br>
  <abbr title="Internet of Things">IOT</abbr><br>
  cite : 웹 문서나 포스트에서 참고 내요을 표시함
  <p>내가 경험한 가장 흥미진진한 일은 누군가를 만나는 일이다 - 영화, <cite>'비포선셋'</cite>중</p>
  code : 컴퓨터 인식을 위한 소스 코드임<br>
  <code>function savetheLocal()</code><br>
  small : 부가 정보처럼 작게 표시해도 되는 텍스트임
  <p>가격 : 13,000원 <small>(부가세 별도)</small></p><br>
  sub : 아래 첨자를 표시함<br>
  <p>물의 화학식은 H<sub>2</sub>0입니다</p>
  s : 취소선을 표시함<br>
  <p><s>34,000원</s>19,000원</
  u : 밑줄을 표시함<br>
  <u>텍스트에 단순히 밑줄 긋기</u><br>
  ins : 공동 작업 문서에서 새로운 내용을 삽입함<br>
  <ins>새로운 내용을 삽입합니다</ins><br>
  del : 공동 작업 문서에서 기존 내용을 삭제함<br>
  <del>기존 내용을 삭제함</del>
  
  <h2>텍스트 태그 여러 개 삽입하기</h2>
  
  <!DOCTYPE html>
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>탐라국 입춘굿</title>
        <link rel="stylesheet" href="css/poster.css">        
    </head>
    <body>
        <div id="container">
            <h3>탐라국 입춘굿</h3>
            <p>탐라국 입춘굿은 입춘을 맞아 풍년을 기원하는 행사로, 제주도의 문화 축제 중에서 유일하게 탐라 시대부터 이어져 왔다.</p>
            <p>제주에서는 입춘을 새철이라 한다. <br>신구간이 끝나 하늘의 1만 8,000 신이 지상으로 내려와 새해 일을 시작하는 때다.</p>
            <p>자세한 정보 보기</p>
            <h4>일정</h4>
            <h4>먹거리</h4>
        </div>
    </body>
</html>
  
  <h2>순서 있는 목록을 만드는 oi,li,태그</h2>
  1.oi태그에서는 type, start 속성을 사용할 수 있다
  2.oi type='a'
  3.순서 없는 목록은 ui태그를 사용한다.
  4.설명목록을 만든 dl,dt,dd태그가 있다
  
  <ol>
    <li>항목1</li>
    <li>항목2</li>
  <ol>
    
 <h2>표를 만드는 table, caption 태그</h2>
    table 태그 안에 tr 태그는 행을 만들고 td 태그는 행 안에 있는 셀을 만들기 때문에 두 태그 모두 모여야 하나의 셀을 만들 수 있음
    
    <table>
    <tr>
      <td>1행 1열</td>
      <td>1행 2열</td>
    </tr?
    <tr>
      <td>2행 1열</td>
      <td>2행 2열</td>
    </tr>
  </table>
