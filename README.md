# self-study
대상

1. html 사용자에게 게시판을 구현한다.
2. 이를 로컬 스토리지를 활용한다.
3. 읽기, 수정, 삭제.
4. 활용기술

HTML
1. CSS
2. 자바스크립트
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
  code : 컴퓨터 인식을 위한 소스 코드임
  <code>function savetheLocal()</code>
