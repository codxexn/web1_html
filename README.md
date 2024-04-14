# web1_Html✍️
**웹개발 (2023.06.12.~2023.11.07.) 강의에서 공부한 HTML 내용**입니다.

readme 파일에 목차 및 내용 정리해두었으니 참고 부탁드립니다.

감사합니다.🥰


<br><br>

## 📝 Day01
> ### Server and Client
- **Service**: 회원들이 이용할 수 있는 것, 사용자들이 사용할 수 있는 기능(ex) 로그인, 회원가입, 뉴스 등)
- **Client**: 서버에게 요청하는 대상
- **Server**: 요청받은 서비스를 응답해주는 대상(서비스 제공) ➡️ computer(server PC)

<br>

📌 **우리의 pc는 서버일 수도 있고 클라이언트 일 수도 있다.**

<br>

> #### URL
> 주소창에 입력된 값: 전체  
> host: server의 주최자: 호스트 부분의 url은 바뀌지 않는다.  
> identification: 뒷 경로(개발자가 필요한 것)  


<br>

> ### Web browser
> 클라이언트는 서버에 요청(request)를 한다.  
> 서버는 클라이언트에게 응답(response)를 한다.


<br>

📌 **browser: 브라우저(창구)**: 클라이언트와 서버가 요청하고 응답할 수 있는 중간 단계

<br>

> **Web: 요청과 응답이 일어나는 장소**  
> 사용자의 요청에 맞는 주소로 찾아가서 인터넷 컨텐츠(문서와 그림, 멀티미디어 파일 등)를 검색 및 열람 후 사용자에게 응답하기 위한 응용 프로그램의 총칭이다.
- 주요 웹 브라우저: 모질라 파이어폭스, 구글 크롬, 마이크로스프트 엣지, 오페라, 사파리 등

<br>

> #### Protocol(프로토콜): 통신 규약
> 사람끼리 소통할 때 서로 이해할 수 있는 공용어를 사용해야 하듯이 컴퓨터끼리도 공용어를 사용해야 한다.  
> 이러한 공용어를 원활하게 통신하기 위해서 필요한 규약을 프로토콜이라고 한다.  
> 사용자의 요청에 반드시 응답하도록 약속한다.

<br>

> #### http://(Hypertext Transfer Protocol Secure Socket)
> SSL(Secure Socket Layer) 프로토콜을 이용하여 자원을 공개키 암호화 방식으로 암호화해서 통신하는 규약

<br>

📌 **Hypertext: 하이퍼텍스트**   
➡️ 문장 중의 어구나 그것에 붙은 표제, 표제를 모은 목차 등이 서로 연결된 문자 데이터 파일

<br>

📌 **http, https(secure, 보안): 약속**   
➡️ 요청을 하면 무조건 응답을 해준다는 약속  
➡️ 인터넷이 연결돼 있지 않아도 연결이 안 됐다는 내용을 응답  

<br>

📌 **SSL(Secure Socket Layer)**   
➡️ 요즘에는 Docker 를 사용해서 socket를 만들 수 있다.

<br>

> #### IP(Internet Protocol)
> 사람이 태어나면 출생신고를 하고 고유번호인 주민번호를 발급받는다.  
> 이를 통해 서로를 구분하듯이 네트워크 상에서 인터넷에 접속할 때 다른 컴퓨터와 구별될 수 있도록 하는 고유번호를 IP주소라고 한다.  
> 클라이언트가 찾아갈 서버의 고유한 값, 컴퓨터가 컴퓨터를 찾을 때 쓰는 고유한 값  

<br>

> #### domain: 도메인
> IP 주소는 기억하고 이해하기 힘들기 때문에 이를 위해서 이름을 부여할 수 있도록 한 것  
> 도메인을 통해 IP 주소를 검색할 수 있다.  
> 아이피 주소로 직접 접근하면 연산이 필요한 부분이 제외되거나 프로토콜이 적용되지 않을 수 있기 때문에  
> **반드시 도메인을 통해 사이트에 접근**하기로 한다.

<br>

> #### WWW(World Wide Web)
> 인터넷에 연결된 전 세계 컴퓨터들을 통해 사람들이 정보를 공유할 수 있는 정보 공간

<br>

> #### W3C(더블유삼씨)
> WWW를 위한 표준을 제정하고 관리하는 중립적인 기관

<br>

> ### Web Standard(웹 표준)
> **웹에서 표준으로 사용되는 기술이나 규칙**을 의미  
> 특정 브라우저에서만 사용되는 비표준화된 기술을 배제하고 W3C의 토론을 통해 나온 권고안을 사용하는 것을 말한다.  
> 웹 문서의 구조와 표현, 그리고 동작을 구분해서 사용하는 것을 의미

<br>

> #### HTML(Hypertext Markup Language): 구조(정보)
- 웹 페이지에서 다른 페이지로 이동할 수 있도록 해주는 마크업 언어

<br>

📌 **마크업 언어란?**  
태그 방법 체계를 의미하며, 태그 등을 이용하여 문서나 데이터의 구조를 기술하는 언어이다.

<br>

> #### CSS(Cascading Style Sheets): 우선순위(디자인)
- 구체적으로 어떤 스타일로 요소가 표시되는 지를 정하는 규격
  
<br>

📌 **HTML**은 문서를 구조화(레이아웃)할 수 있으나 꾸밀 수 없다.  
📌 **CSS**를 통해 디자인하여 웹 페이지에서 내용과 스타일을 분리하고 역할도 분리해준다.

<br>

> #### JS(Javascript): 화면 쪽에서 연산이 가능한 스크립트 언어
- 사용자의 다양한 이벤트 처리, 비동기 통신 등을 자유롭게 사용 가능
- HTML 안에서 태그 형태로 JS 사용 가능하며, 외부 파일로 제작 후 포함시켜 사용할 수도 있다.
- 유효성 검사, 통신 등을 담당

<br>

> #### XHTML(Extensible HTML)
- 기존에 사용되던 HTML 규격이 가진 문제점을 극복하고 보다 다양한 분야에 응용될 수 있도록 해주는 여러가지 **확장된 기능을 포함**한다.
- 하지만 XML기반으로 만들어졌기 때문에 지원되지 않는 브라우저도 있다.
- 따라서 HTML과 XHTML은 사실상 큰 차이 없이 사용된다.

<br>

> #### XML(Extensible Markup Language): 서버간 데이터 교환에 필요한 것(비슷한 것: JSON)
- 어떠한 데이터를 설명하기 위해서 임의로 지은 태그로 데이터를 감싼다.
- 태그로 데이터를 설명 ➡️ 데이터의 표시(Markup)가 된다.
- 추가적인 데이터가 생기면 태그 추가와 태그 내부 내용 추가를 할 수 있다.
- 데이터 전달이 목적
```html
<?xml version="1.0">
  <user>
    <userId>no1zeus</userId>
    <name>제우스</name>
  </user>
```

<br>

📌 **Cascade**  
➡️ **DBMS**: 부모를 지우면 자식까지 모조리 다 지워버리겠다는 의미(부모부터 자식까지)  
➡️ **CSS**: 우선순위

<br>

> ### Web Server(웹 서버)

📌 **사용자가 요청한 것이 정적데이터인지, 동적데이터인지 구분**

<br>
  
➡️ 클라이언트가 요청할지 안할지
- 미리 알 수 없는 것: 동적데이터
  - 연산이 필요함(웹컨테이너(java, ...) 필요)
    - 복잡한 연산: DB 조회 ➡️ java
    - 단순한 연산: 예) 아이디 입력했니? ➡️ JS
- 미리 알 수 있는 것: 정적데이터
  - 웹 컨테이너가 결과를 주면 정적데이터가 되기 때문에 웹 서버가 처리 가능
  - 웹 서버는 정적만 처리

<br>

> #### WAS(Web Application Server)
> WAS를 통해 웹서버 - 웹컨테이너 소통  
> 예) Tomcat(톰캣)
 
<br>

📌 **How to install Tomcat**
```
톰캣설치 구글에 톰캣 검색 -> download 9 -> 64-bit Windows zip (pgp, sha512)

resource 에 붙여넣고 C드라이브에 복붙해서 압축 풀기

bin -> startup(Windows 배치파일) 클릭했을 때

cmd가 바로 꺼지지 않고 결과가 쭉 나오고 

마지막 문장에 start 가 있어야 함

(19-Jul-2023 21:12:33.568 INFO [main] org.apache.catalina.startup.Catalina.start ?쒕쾭媛 [3339] 諛由ъ큹 ?댁뿉 ?쒖옉?섏뿀?듬땲??
덈떎.)

바로 꺼지면 환경 설정 -> 시스템 속성 -> 환경 변수 설정이 제대로 안 돼 있다는 의미


conf -> server(메모장 연결) 복붙하고 (9000) 으로 바꿈
() 안의 부분!!
(
-->
    <Connector port="9000" protocol="HTTP/1.1"
               connectionTimeout="20000"
               redirectPort="8443" />
)

그리고 저장, 닫고 다시 bin -> startup 실행 후
크롬에 localhost:9000 주소창에 입력

Eclipse 연동
서버 끄고!!!! 이클립스 html -> resourse에 깔기

servers 두고 다 끄기

Dynamic Web Project

Window - preferences - server - Server and Runtime 9.0

Environments - 모두 삭제하고 Add 9.0 next -> Browser (C:\apache-tomcat-9.0.78)


enc - Workspace - UTF-8

CSS HTML JSP 모두 UTF-8 로 APPLY

Servers - 9.0 Next - Finish - 클릭하고 재생
```

<br><br>

## 📝 Day02
> ### html
> Webcontent에 생성

<br>

> #### HTML의 요소
```html
  <p> ¹
    You are the best ²
  </p> ³
```
　¹　**여는 태그(Opening tag)**: 요소의 이름(p)과 열고 닫는 꺽쇠 괄호로 구성된다.  
　²　**내용(Content)**: 요소의 내용이며, 단순한 텍스트를 의미한다.  
　³　**닫는 태그(Closing tag)**: 요소의 이름 앞에 슬래시(/)가 있다.

<br>

📌 **html 주석**: <!-- 주석 -->: Ctrl + Shift + /  
📌 **<> 태그**: 연 것은 무조건 닫아야 한다. single tag 는 안 닫기도 한다.

<br><br>

## 📝 Day03
> ### HTML 요소의 종류

<br>

> #### 블럭 요소
> **p, h, ul, ol, div, form, table,...** 등
- 코드 상에 한 줄로 이어 써도 화면 상에서는 앞 뒤 요소 사이에 새로운 줄을 만들어서 나타난다.
```html
<p>apple</p><p>banana</p>
```
⬇️ **화면**
```
apple
banana
```
- 영역이 정확히 구분되어 있기 때문에, width, height 속성을 수정할 수 있다.
- margin-top, margin-bottom 속성도 잘 적용된다.
- padding-top, padding-bottom 속성도 잘 적용된다.
- div 태그
  - 다른 HTML 요소들을 하나로 묶는 데 사용되는 대표적인 블록 요소이다.
  - 주로 여러 요소들의 스타일을 한 번에 적용하기 위해 div 태그를 사용한다.

<br>

> #### 인라인 요소
> **span, a, img, strong, em, ...** 등
- 새로운 줄을 만들지 않고 작성한 단락 내에 나타난다.
- 안에 있는 내용만큼만 영역을 차지한다.
```html
<strong>apple</strong><em>banana</em>
```
⬇️ **화면**
```
applebanana
```

📌 **인라인 요소를 중간 정렬하고 싶으면 블록 요에 넣고 센터 정렬**

- 영역이 불분명하기 때문에 width와 height를 임의로 부여할 수 없다(img 태그 제외)
- margin-top, margin-bottom 속성도 적용되지 않는다.
- padding-top, padding-bottom 속성도 적용되지 않는다.
- span 태그
  - 텍스트의 특정 부분을 묶는 데 자주 사용되는 요소이다.
  - 주로 텍스트의 특정 부분에 따로 다른 스타일을 적용하기 위해 사용한다.

<br>

> #### 인라인 블록 요소
> **button, input, select, ...** 등
- inline 요소와 동일한 영역(내용만큼)을 가지지만 width와 height를 설정할 수 있다.
- margin-top, margin-bottom 속성도 잘 적용된다.
- padding-top, padding-bottom 속성도 잘 적용된다.

<br>

> #### format: 서식 태그
```html
    <br>: 줄바꿈
    <p>: 문단(paragraph)
    <b>, <strong>: 굵게(bold) ➡️ strong 사용 지향
    <del>: 취소선
    <ins>: 밑줄
    <i><em>: 이태리체
    <mark>: 형광펜
    <sub>: 아래 첨자
    <sup>: 위 첨자
    <h#>: 제목(크기 키워줌, 숫자 작을수록 큼)
    <a>: 하이퍼링크
      <a href = "링크 주소" target = "_self": 현재 페이지/ "_blank": 새 페이지>
    <q>: ""
```

<br>

📌 **내용을 명령어로 인식하지 못하게 하는 문법**
```html
    &lt;: less than: <
    &gt;: great than: >
    &amp;: ampersand: &, and
    &quot;: 인용하다, 전달하다: "
    &nbsp;: 공백
```

<br>

> #### list
- **순서 없는 리스트**
```html
<ul>태그 안에 <li>태그 사용

    <ul>
      <li>텍스트1</li>
      <li>텍스트2</li>
      <li>텍스트3</li>
    </ul>
```
- **순서 있는 리스트**
```html
<ol>태그 안에 <li>태그 사용

    <ol>
      <li>텍스트1</li>
      <li>텍스트2</li>
      <li>텍스트3</li>
    </ol>
```
- **type 속성**: 1, A, a, i, I
- **type 속성 사용 예시**
```html
  <ol type ="속성값" start ="시작값">
```

<br>

> #### table
```html
    <table border="1" 표 선></table>
    <th>: 표 가장 상단열(굵게, 가운데 정렬)
    <tr>: 행
    <td>: 열
    <caption>: 표 제목
```

<br>

> #### head
```html
<style>
  td {
    text-align:center ➡️ 중앙 정렬
    font-weight:bold ➡️ 글씨체 두껍게
  }
  
  table {
    width: 30%; ➡️ 표 가로길이 화면기준 30%
    border: 1px solid black; ➡️ 표 테두리 단선 블랙
    border-collapse: collapse;
    			- collapse : 서로 이웃하는 테이블이나 셀의 테두리선을 겹쳐서 표현 합니다.
    			- separate : 기본값으로 서로 이웃하는 테이블이나 셀의 테두리선을 분리시켜 표현 합니다.
    margin: 0 auto; ➡️ 표 바깥여백 상하 0 좌우 자동
  }
</style>
```
