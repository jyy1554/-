## 웹사이트 구축 순서 : I.구상 - II.기획 - 디자인 - 개발 ↔ 테스트(QA) - 완성
## Start Small
##
## I. 구상 : 왜 만드는가?
##
## II. 기획 : UI 모델링(사용자의 입장에서 동작하는 기능을 가상으로 만들어보기)
### UI : 사용자가 시스템을 제어하는 조작장치
### pencil : 무료, http://pencil.evolus.vn/
### balsamiq : 유료, https://balsamiq.com
### 손그림, PPT
##
## 인터넷 : 도로. 데이터를 주고받을 수 있는 가장 큰 네트워크
## 웹 : 대중교통. 전세계에 깔려있는 인터넷을 이용해서 HTML파일을 주고받을 수 있는 기술 by. 팀버너스리
## 최초의 구성 : 웹브라우저 <----- HTTP / HTML -----> 웹서버
##
## 서버 : 응답하는 쪽. 웹서버가 설치된 컴퓨터. (bitnami설치-apache, mysql, php)
## 클라이언트 : 요청하는 쪽. 웹브라우저가 설치된 컴퓨터. 
##
## Bitnami 사용법
## localhost/index.html 입력
### localhost : 웹브라우저가 설치된 컴퓨터
### htdocs 디렉토리 : Document Root 라고도 함. 웹서버가 문서를 찾는 최상위 디렉토리. 
## C:\Bitnami\wampstack-7.3.24-0 에서 manager-windows 실행 : apache가 running 되어있어야함
##
## 프로그래밍 언어 : 사람과 컴퓨터 사이의 약속
## 코드 : 설계도. 
##
# HTML 궁극적인 목표 = 정보! 어떤한 정보를 컴퓨터와 사람이 이해할 수 있게 태그를 이용해서 규정하고 정의하는 것!
## HTML : Hyper Text (연결,링크된) Markup Language (Tag : 설명하는 정보)
## <!DOCTYPE html> : html5를 따른다. 
## 태그 : head(문서에 대한 정보를 담은 태그), body(본문 해당), a, li, ul (=unordered list), ol
### 태그 검색 : http://dev.w3.org/html5/html-authhor 또는 http://opentutorials.org/course/1058
## 속성 : 띄어쓰기로 구분 e.g. href="링크", target="_blank"
