#### 작업예정.
-UI 계속진행 (VS code)하면서,
-피곤할때 자바|스프링(이클립스-egov전자정부프레임워크개발환경)  기본실습진행.
-피곤할때, 오라클DB(SQL디벨라퍼개발환경) Ansi=SQL((표준 SQL)기본실습진행CRUD.
-2달째부터(백엔드),주로 스프링으로 실습이 진행(납품용-이력서포트폴리오용).
-egov:자바기반 -> JDK(Java Delvelopment Kit자바개발환경)설치확인.
-JDK 실행 경로 추가.
-java -version(git --version)
-자바 오라클자바는 8버전부터 돈을 내야 합니다. 이슈때문에, 오픈JDK
-그래서, 오라클자바 8~11버전 지우고, 오픈JDK로 변경 후 이클립스를 사용할 예정.
-OPEN JDK 8버전(egov와 100%호환됨)사용함.
-톰켓 : 이클립스에서 웹프로그램 결과를 확인하는 라이브 서버 입니다.(localhost:8080)
-라이브서버(아파치): VS code에서 HTML 결과를 확인하느 라이브 서버(localhost:5500)
#### 20210520(목) 작업.
-메인페이지 시간이 걸리는 부분(프런트엔드): 메뉴처리, 슬라이딩처리OK.
-모바일 게시판페이지(CRUD) CSS 처리
-카멜표기법 (낙타등표기법 예, .bbsListTb1), _표기법(예, .bbs_title)
-href헤르프 : hypertext refrance(웹 문서 참조)
-정적(static) 콘텐츠 : html,css,js
-동적(dynamic) 콘텐츠:jsp(java스프링),py(python장고),PHP,c#(닷넷),Nodejs(익스프레스)
-오후에 자바 (스프링) 개발환경 설치예정 .(이클립스:전자정부 표준 프레임워크의 개발환경을 설치)
-게시물 타이틀 넘치는 부분 CSS처리했음. jsp에서 프로그램으로 처리할 예정
-모바일 서브페이지 CSS 스타일처리
-테블릿+PC용 CSS 스타일처리
-테블릿+PC용 CSS 스타일처리
-모바일+테블릿+PC 댓글시스템 CSS+제이쿼리+부트스트랩 처리
-AdminLTE(부트스트랩기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
-UI디자인 끝 -------------------------------------------
-UI구현 시작 ------------- 스프링프로젝트 시작(이클립스+자바+오라클+스프링)
-UI구현 ......위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210518(화) 작업예정.
-메인페이지 테블릿 메인CSS 스타일 처리,pc용 메인CSS 스차일처리(반응형으로 저작)
-반응형 페이지의 핵심기술은 미디어쿼리 명령어 사용+ 가로크기를 %로 지정
-미디어(pc화면,스마트폰화면,프린터,테블릿화면)+쿼리(질의어=질문)
-@emedia 미디어타입(screen,print 등등=all) and (min-width:801px){스타일 구현내용}
-테블릿은 마우스 오버 기능을 넣을 필요가 없습니다.(손가락으로 선택을 하기 때문)
-배치1:jQuery코어 임포트 이후에 사용자가 지정한 js 배치를 해야함.
-배치2: reset.css,mobile.css 임포트 이후에 사용자가 지정한 tablet.css,pc.css 배치해야 레이아웃이 깨지지 않습니다.
-메인페이지 시간이 걸리는 부분(프론트엔드):메뉴처리,슬라이딩처리
-메인페이지 시간이 걸리는 부분(백엔드):최근갤러리,공지사항 DB데이터를 출력하는 부분
-보통 1주일정도 걸립니다.
-테블릿 메인 CSS 스타일처리, PC용 메인 CSS 스타일 처리
-모바일 서브페이지 CSS 스타일처리
-테블릿+PC용 CSS 스타일처리
-모바일 게시판페이지 (CRUD) CSS처리
-테블릿 + PC용 CSS 스타일처리
-모바일 + 테블릿 + PC 댓글시스템 CSS + 제이쿼리 + 부트스트랩 처리 
-Admint TE(부트스트랩기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
-UI 디자인 끝------------------------------------------------
-UI구현 시작 ---------------- 스프링프로젝트 시작(자바 + 이클립스 + 오라클 +스프링)
-UI구현 --------위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210517(월) 작업예정
-jQurey 제이쿼리 JSON 데이터 파싱
-외부 data.js 파일에서 json데이터를 저장한 후 html 에서 불러와서 파싱.
-외부 사이트에서 제공하는(RestAPI서버) json 데이터를 html에서 불러와 파싱.
-ReatApI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에뿌려주는 작업)
-외부 data.js 파일에서 json데이터를 저장한 후 html에서 불러와서 파싱.
-외부 사이트에서 제공하는(RestAPI서버) json데이터르 html에서 불러와 파싱.
-ReatAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱 (데이터를 분해해서 화면에 뿌려주는 작업)
-ReatAPI서버주소(빅데이터) : https://coroname.me/getdata
-메인페이지에 자바스크립트(jQuery)적용.(VS code+HTML5+CSS+jQuery)
-제이쿼리적용부분:메뉴,슬라이드이미지3개 처리:모바일 메인페이지만 마무리
-보통 이미지 슬라이드 처리는 외부 라이브러리(Lip)사용(니보슬라이드,캐러셀슬라이드)
-외부 Lip 사용 안하고
-테블릿 메인 CSS 스타일처리, PC용 메인 CSS 스타일 처리
-모바일 서브페이지 CSS 스타일처리
-테블릿+PC용 CSS 스타일처리
-모바일 게시판페이지 (CRUD) CSS처리
-테블릿 + PC용 CSS 스타일처리
-모바일 + 테블릿 + PC 댓글시스템 CSS + 제이쿼리 + 부트스트랩 처리 
-Admint TE(부트스트랩기반템플릿-반응형)를 이용해서 관리자단 디자인 만들기
-UI 디자인 끝------------------------------------------------
-UI구현 시작 ---------------- 스프링프로젝트 시작(자바 + 이클립스 + 오라클 +스프링)
-UI구현 --------위 에서 제작한 UI디자인 이용해서 프로그램을 입히게 됩니다.

#### 20210514(금) 작업예정
-구문오류 : syntex 신택스(사인택스)오류(문법오류)
-CSS,HTML5 : 유효성 검사기준입니다.
-사용자단 모바일 메인페이지 footer영역 CSS입히기.
-top상단이동 OK.
-과제물 제출 준비
-jQuery Json 데이터 파싱연습
-메인페이지에 자바스크립트(jQuery)적용,
-메뉴 ,슬라이드 이미지처리, top상단이동


#### 20210513(목) 작업내역
-픽사베이 이미지 3개 : 로고1, 슬라이드 이미지1, No이미지1 받고 경로적어놓기
-로고:https://pixabay.com/ko/illustrations/%ED%8A%B8%EB%A6%AC-%EC%83%9D%EB%AA%85%EC%9D%98-%EB%82%98%EB%AC%B4-%EC%95%A1%EC%9E%90-%EC%98%81%EC%A0%81-5334823/
-슬라이드 이미지:https://pixabay.com/ko/illustrations/%EC%B1%85-%EC%98%A4%EB%9E%98-%EB%90%9C-%EA%BF%88-%EA%B3%B5%EC%83%81-863418/
-No이미지:https://commons.wikimedia.org/wiki/File:No_image_available.svg
-작업폴드를 나누는 이유 : 시청(관공서), 대학, 기업의 웹프로그램(사이트)제작 할때, 1년간 무상 유지보수 그 이후 보통 2천, 리뉴얼 4천 비용이 책정
-home폴더 기존작업물, 리뉴얼 home에 덮어씌우는 방식이 아니고, 리뉴얼 할때 home2022 폴더에 작업을 하게 됨.
-jquery코어 다운받기: min버전(압축-속도UP), 일반버전(개발-속도Normal)
-jQuery 미처리 작업은 다음주하고,
-오늘부터는 모바일 메인페이지 1개 만들어서 과제물로 제출 -> 스프링에서 프로그램 입히는 소스로 사용하게 됩니다.
-애니데스크(독일산): 팀뷰어(독일산) 사용하는 대신에 애니데스크르 사용.
-html5.html, css.html, js.html 여기까지
-jQuery 기본구조만 실습했습니다.

#### 20210512(수) 작업내역
-다른곳에서 작업할때
-git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해 주셔야합니다.
-git config --list확인에서 user.name, user.email 없으면 아래추가.
-터미널에서 아래 2가지 실행
-git config  -local user.name 영문이름
-git config  -local user.email 영문이메일
-프로젝트를 1명이 제작하는 경우가 없기 때문에,2명일때 소스수정한 사람 확인용 정보 입니다.

#### 20211011(화) 작업내역
-로렘 입숨 한글URL:
-로렘 입숨 영어URL:
-경로(path): /루트, /test/html5.html
-html5의 레이아웃 구조 제작합니다.
-서버 (응답하는프로그램=response) = 아파치서버,톰캣서버
-클라이언트 (요청하는프로그램=request) = 웹브라우저
-HTML은 마크없이 태그로 구성됩니다.<의미있는문자>...</의미있는문자>...</의미있는문자>
- http://127.0.0.1:80[8080|9000|5500|6500]
-pc의 네트워크 내부주소(공통): 217.0.0.1 ==localhost
-고유주소: yahoo.com(도메인) == 74.6.163.25(ip주소) ==주민번호
-IP주소버진: IPv4, IPv6
-HTML도 버전: HTML5, HTML4.02(old)

#### 20210510(월) 작업내역
-업로드절차 1.커밋(commit) 2. 푸시(push)
-다운로드절차: 1.풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 상황
-레포지토리(저장소) 초기화 : git init
-개발pc(html)과 깃 저장소와 연결시킵니다.
-포트의 역할이 트렌드로 많이 사용됩니다.
-포트(port):포트번호로 서비스르 만드는것이 트렌드
-이전에는 80포트에 모든 서비스 묶어놓았습니다.
-모든서비스를 개별로 분리하는 트렌드가 있습니다. :마이크로서비스라고 합니다.== RestAPI로 구현이 됩니다.
-도메인(예, https://naver.com:1251241/네이버 인증서비스 개발)
-외부인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용
-html : Hyter Text MarkUp Language 태그를 사용하는 언어
-md : MarkDown Language 태그를 사용하지 않는 언어