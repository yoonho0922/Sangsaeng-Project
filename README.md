2020년 1학기 상명대학교 스터디 상생플러스의 개발 프로젝트 repository입니다.   
Javascript 기반 Web/Mobile application 개발 플랫폼 Meteor를 이용하여 영어기사를 보며 영단어를 학습할 수 있는 웹사이트 개발   
<br/><br/>
[Meteor](https://www.meteor.com/)
<br/>
html, css, javascript  
Node.js, npm  
mongoDB  

## Run Project
#### install meteor
* [미티어 설치](https://www.meteor.com/install)
#### npm install (최초 1회 실행)
```
meteor npm install
```
#### run
```
meteor
```
* 실행 후 웹브라우저에서 localhost:3000 접속  (```meteor run --port <port number>```로 포트번호 지정 가능)
* Sign up 또는 Login. admire@gmail.com으로 signup하면 관리자 계정임
* localhost:3000/postingAuto에서
[The Korea Herald](http://www.koreaherald.com/index.php) 기사의 링크를 scraping한 후 upload하여 기사 업로드 가능

## Document
* [페이지 구성](/docs/client_structure.md)
* [DB 구조](/docs/DB_collection.md)
* [추가한 package](/docs/npm_install.md)
* [참조](/docs/reference.md)

## Project Structure
* Client : 화면 구성 모음
* docs : 정리한 문서 모음
* public : 사진 파일 등 모음
* server : 백엔드 관련
* lib : html HEAD, 라이브러리, 함수 등..  

