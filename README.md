#### 작업예정.
-UI 계속진행 (VS code)하면서, 
-피곤할때 자바|스프링(이클립스-egov전자정부프레임워크개발환경) 기본실습진행. 
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
#### 20210524(월) 작업예정
-시간형식(type):date(년월일),dateTime(년월일시분초),TimeStampt(년월일시분초)
-1970년 생일:타임스탬프가 1970년1월1알 부터 현재까지의 초를 계산한 결과 값.
-1970년1월1일부터 16억2천...초가 흐른시간이 현재시간.
-팝업창:모달창(modal-필수창:작업후 다음창으로 가능), 모달리스창(modalless-작업하고 상관없이 다른창으로 이동가능)
-폰트어썸(아이콘웹폰트): 아이콘을 확대해도 깨지지 않음(백터방식의 아이콘)
-포토샵 디자인으로 아이콘을 만들면 확대시 깨진다(스킬라방식의 아이콘)
-부트스트랩 그리드(모눈송이)레이아웃: 화면을 12개의 컬럼으로 분리해서 크기를 반응형으로 만듭니다
-row(가로줄), cols(세로칸), col-md-12 (화면가로 크기를 12로 지정=100%, 조검은 md미디엄에서는 100%)
ㅡ반응형의 화면크기:xs엑스트스몰(~750px), sm스몰(750px), md미디엄(970px), 1g라지(1170px~)
-화면의 가로크기를 지정하는 이유(모바일,태블릿,PC용일때 가로크기를 지정하기 위해서 입니다.)
-col-6(화면의 가로크기를 6으로 지정=50%)
-border_view.html 댓글 UI디자인(부트스트랩) 추가.
-반응형 서브페이지들 (로그인,회원가입,마이페이지).
-관리자단 AdminLTE적용 (회원관리CRUD,게시판CRUD,대시보드)
-이클립스 헬로월드 실습. 1.다이나믹 웹 프로젝트(jsp만드는 방식)만든후 사용자단 UI실행만,하고 삭제.
-jsp(1세대 2000년-게시판)->서블렛(2세대servelet게시판) ->스트러츠(3세2010년대프레임워크) -> 스프링(4세대2013년대이후,프레임워크)
-스프링(MVS)웹 프로젝트 만들예정. 헬로월드 1개 -2달간 이프로젝트로 진행
-위 스프링 프로젝트에서 자바 기초도 이것으로 실습할 예정. ->htmlUI만들것을 jsp변경작업 들어갑니다.
#### 20210521(금) 작업.
-반응형 게시판페이지(CRUD) CSS 처리 : Create(Update) = board_write.html
-글쓰기폼(부트스트랩을 적용):제이쿼리부분, 내용입력부분 웹에디터 추가.
-부트스트랩(AdminLTE): 제이쿼리 기반의 UI 템플릿(프레임워크)
-adminLTE:dist(디스트리뷰트=배포),pages(더미데이터),plugins(서머노트등등)
-대시보드파일샘플: index.html, index2.html,index3.html
-board_write.html 파일에 bootstrap코어임포트 + 서머노트플러그인 임포트
-board_view.html 댓글 UI디자인(부트스트랩)추가.
-반응형 서브페이지를 (로그인,회원가입,마이페이지).
-관리자단 AdminLTE적용.(회원관리(RUD,게시판CRUD,대시보드)
-톰켓(class해석)  vs  VS라이브서버(아파치-html해석)
-자바소스(.java앱,.jsp웹) -> 컴파일(라인단위X-인터프리터X) -> class파일(여기에 DB자료가 동적으로 입출력이 됨) -> html번역(WAS-톰켓) -> 크롬(IE)화면에 렌더링 결과
-localhost도메인 =127.0.0.1 아이디와 바인딩되는 도메인.
-이클립스 헬로월드 실습 1.다이나믹 웹프로젝트 만들예정.헬로월드 1개-2달간 이프로젝드로 진행
-백엔트:1.이클립스(스프링)
-2.스프링 (MVC)웹 프로젝트 만들예정. 헬로월드 1개-2달간 이프로젝트로 진행합니다.
-위 스프링 프로젝트에서 자바 기초도 이것으로 실습할 예정->htmlUI만들것을 jsp변경작업 들어갑니다.


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