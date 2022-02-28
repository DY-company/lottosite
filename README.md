# 로또번호추첨 사이트 만들기

## 백엔드의 개념과 프레임워크 구조를 이해하며 로또 번호 추천 사이트 만들기

* 개념
  - 백엔드(Backend)란? 우리가 화면에서 볼 수 없지만 웹이나 앱에서 사용자 요청에 따라 정보를 처리하고 가공하는 부분
  - 프레임워크(FrameWork)란? 백엔드를 바닥부터 개발하기에는 구조가 조금 복잡하여 이미 많은 것이 갖추어진 어떤 틀안에서 작업하는 것
어떤 구조로 만들었는지, 어떤 언어를 사용하는지에 따라 다양한 프레임워크가 있다.

* 프레임워크 구조 이해하기
  -
  <img src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2F20140930_142%2Fyysvip_1412065980906wpRBJ_PNG%2Fmvcpattern.png&type=sc960_832" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br> 
    ① Front-end에서 http://doyun.com/board 
        ->doyun.com에 게시판(board)라는 URL로 접근<br> 
    ② 라우터(Router)에서는 "borad" 서브URL 읽어서 우리가 게시판을 접근할 것을 알아낸다.<br>
    ③ 라우터는 컨트롤러에게 게시판이 왔다는 것을 알려준다<br>
    ④ 컨트롤러에서는 게시판에서 해야 할 일 저장하고 있어서 먼저 모델을 통해 DB에서 게시글 정보를 가져옵니다.<br>
    ⑤ 가져온 정보를 view를 통해 html, css첨가 한 후 화면으로 전달<br>
  
 
