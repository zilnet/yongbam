# 프론트 앤드 기초 수업

## GITHUB 기초 개념

>GITHUB 용어

- stage : commit할 대상을 선택
- commit : 수정한 내용의 스냅샷을 찍음
- push : GTIHUB 서버에 업로드
- pull : GITHUB 서버에서 다운로드
- branch : 각각의 개발자가 독립적으로 개발하기 위한 가지
- pull request : 각각의 branch에서 개발한 것을 master branch로 병합하기 위한 요청
- merge : 각각의 branch에서 개발한 것을 master branch로 병합하는것

+stage (staging) -> 무대위에올린다 (10군데 수정한곳 중에 5군데만 스냅샷을 찍고싶으면 
+커밋할것을 표시하는거를 스테이지라고한다

+stage -> commit -> push (내컴터에 저장되어있는거 업로드) 버젼관리 기본 3단계
+pull 깃허브 내에 찢어진거 합친거를 다시 토탈 다운로드

+협업관련 branch (사전적의미 가지치기 등)
+pull request (땡겨달라고 요청)

> 사이트 링크
마크다운 사용법 : [안내문서](https://gist.github.com/ihoneymon/652be052a0727ad59601)<BR/>

HTML, CSSS, OS참고 사이트 : [W3SCHOOLS](https://www.w3schools.com/python/default.asp)

온라인 에디터 : [CODE PEN](https://codepen.io/)

이거 엄청재미<br/>있네??ㅋㅋ

## WEB/IT 기초개념

>>클라이언트-서버 모델

<img src="https://github.com/zilnet/yongbam/blob/main/%EC%9D%B8%ED%84%B0%EB%84%B7%EA%B7%B8%EB%A6%BC1.png?raw=true" width="648px"/>
-클라이언트 서버 모델에서 클라이언트는 사용자가 사용하는 디바이스 (PC,Mibile)을 의미하고, 서버는 클라이언트가 접속해서 데이터나 파일을 요청했을때 응답하는 시스템이다 (이것또한 컴퓨터'서버
 - 클라이언트와 서버는 네트워크를 통해서 연결됨


<img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/2614/4971.png" />
-클라이언트와 버 모델은 실제 연결은 아니지만 개념적으로 클라이언트 관점에서 1:1로 연결되었다고 생각할 수 있음
 - 클라이언트 서버 모델에서 이루어지는 동작들은 클라이언트의 요청 (request)과 서버의 응답)response)의 한 사이클로 구성됨
 - 클라이언트는 클라이언트 디바이스에서 실행되는 웹브라우저, 서버는 서버 디바이스에서 실행되는 서버 소프트웨어가 실제로 사용되는 것임.

## HTML

> [HTML Introduction](https://www.w3schools.com/html/html_intro.asp)<br/>

> [HTML Elements](https://www.w3schools.com/html/html_elements.asp)<br/>

> [HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)<br/>

HTML 속성(attributes)
1) HTML Element에 추가 정보를 제공
2) name = "value" 형태로 사용
3) 멀티미디어(비디오,오디오)

### 텍스트 컨텐츠 요소[Elements]
웹 문서에서 표시 할 수 있는 컨텐츠

> [HTML Headings](https://www.w3schools.com/html/html_headings.asp)

제목 태그(tag)
Heading -> h
h1 ~ h6

> [HTML paragraphs](https://www.w3schools.com/html/html_paragraphs.asp)

단락 태그
Paragraph -> p

수평선
Horizontal Rules -> hr(Empty Element)
시작태그만 있는 태그

> [HTML Links](https://www.w3schools.com/html/html_links.asp)


하이퍼링크
anchor -> a
href : 링크로 연결된 목적지 주소
1) 외부링크
 - 링크 주소 입력 시 http(https)키워드를 사용

2) 북마크
 - 목적지에 id attribute를 사용해서 이름을 정해줌
 - href attribute에 #를 사용해서 목적지 이름을 입력
 
[HTML Tables](https://www.w3schools.com/html/html_tables.asp)

[Table Generator](https://www.tablesgenerator.com/)

[HTML Lists](https://www.w3schools.com/html/html_lists.asp)
1) 순서없는 목록(ul)
2) 순서있는 목록(ol)
3) 설명 목록

ul, ol목록 사용 시 중첩(nasted)형태로 사용.
- 포함하는 목록 항목에 작은 목록 전체가 포함됨.
