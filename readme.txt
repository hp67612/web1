HTML 태그

1. 강조 태크
<strong>웹페이지 멋찜</strong>  
-> 진하게(굵게)

<strong>웹페이지 <u> 멋찜</u></strong>
-> "멋찜"만 밑줄 <u> 멋찜</u> 


2. 제목(heading) 크기 태크
일반적인 text보다 두껍고, 자동 줄바꿈이 됨
h의 숫자가 높을수록 글씨가 작음

-><h1>내가 좋아하는 과일</h1> 제일 큰 글씨
   <h2>내가 좋아하는 과일</h2>
   <h3>내가 좋아하는 과일</h3>
   <h4>내가 좋아하는 과일</h4>
   <h5>내가 좋아하는 과일</h5>
   <h6>내가 좋아하는 과일</h6>


3. 문단 혹은 단락(paragraph)은 p 태그
<p>This is a paragraph.</p>
정해져있는 간격만큼만 벌어짐

4. 문단 내에서 br 태그로 줄바꿈(한줄띄기)
-> <br> 
    줄바꿈이기 때문에 닫지 않는다. 
    여러번 사용할 경우 칸을 띄울때 사용가능하지만 시각적으로 지저분해짐

5. 이미지 삽입태그
<img src="read.jpg" width="100%">
src-이미지파일명, width-이미지를 화면에 맞추는 코드

예>
<img src="./html_css_배우기/read.jpg" width="50%">
./-현재 폴더아래
html_css_배우기/-그림파일 위치 폴더이름
read.jpg"- 그림파일명
width 속성 - 자동비율유지되계 조절가능

6. 목차(list)태그 (li는 부모태그가 같이다님)
<li>내용</li> - 내용 앞에 가운뎃 점이 찍힘

<ul>태그 - 그룹핑을 하기 위한 부모태그
- 여러 항목의 연관성의 경계를 짓기위한 태그

예>
<ul>
  <li>1. HTML</li>
  <li>2. html_css_배우기</li>
  <li>3. javaScript</li>
</ul>

<ol>-숫자 자동 넘버링

예>
<ol>
  <li>HTML</li>
  <li>html_css_배우기</li>
  <li>javaScript</li>
</ol>

7. 표만들기 태그(3개가 set)
<table>
  <tr> - 표의 첫째줄
      <td>표안에 들어갈 내용</td>
      <td>옆칸에 들어갈 내용</td>
  </tr>    
  <tr>
      <td>표안에 들어갈 내용</td>
      <td>표안에 들어갈 내용</td>
  </tr>  
 </table>

 8. 웹페이지 제목태그(본문의 제목을 설명하는 태그)
 <title>Web1 - html</title>

  9. 웹에 표시되는 사용코드 명령태크(본문에 표시되는 코드를 설명)
  <mata charset="utf-8">
  -> "utf-8"코드로 웹페이지에서 보여지게 하는 태크임.
   html 작성코드를 명령해줘야 웹페이지에서 안깨지고 보임

   10. 본문을 설명하는 태그를 묶는 상위태그
   <head></head>

   11. 본문을 묶는 태크
   <body></body>
   
   12. head태크를 묶는 상위 태그
   <html></html>
  
   13. html 시작전 표시하는 태그
   <!doctype html> - 맨 첫줄에 선포하고 시작

   예> html 기본구성
   <!doctype html>
    <html>
      <head>
        <title></titel>
        <meta charset=utf-8">
      </head>  
      <body>
      </body>
    </html>

  14. 링크태크<a></a>
  <h1><a href="https://www.w3.org/TR/html51/introduction.html#html-vs-xhtml"
  target="_blank">HTML이란 무엇인가?</a></h1>
  링크를 걸고 싶은 글자를 <a href="url주소" target="_blank"></a>태그로 감싸면 됨
  href="링크주소" 
  target="_blank" - 링크를 새탭으로 열고 싶을때 쓰는 코드 

  . CSS
  -> 태그와 태그사이에 여백을 나타내는 코드(문단을 원하는 간격만큼 떨어뜨릴 수 있음)
  <p>태크와 함께 사용가능하며 enter로 CSS코드를 분리해주면 색깔이 노란색으로 바뀌며 활성화된다. 
  <style="margin-top:40px;"> - 위쪽 여백을 주고 싶을때

  예>
  <p style="margin-top:45px;">당귤은 스위트오렌지(sweet orange)라고도 불리는데, 이는 <<strong>비터오렌지(bitter orange)</strong>로
  불리는 쓴귤 등 "오렌지"라 불리는 다른 귤속 식물의 열매와 구분하기 위해서이다.</p>

  -> 글자크기 코드
  <span style="font-size:22px;"> </span>


