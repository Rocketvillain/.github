# RocketVillain

## 💻 `프로젝트 소개`
> 원래 가던 우리 아이의 병원, 진료만 가능하다고?  
> 어디가 좋은 병원인지 알고 싶어요!  
> 전화로만 하는 불편한 예약  
> 강남 지역 동물 병원을 전체 조회하고 중간에서 빠르게  
> 해당 병원에 예약을 해주는 **강남 동물 병원 예약 시스템**🏥  
> `우리 아이를 가장 안심되는 곳에 맡길 수 있는 서비스!`  
> ***HealingPets***

## 🌟 `개발 기간`

- 2024년 8월 27일 ~ 2024년 10월 10일

## 🧑‍🤝‍🧑 `멤버구성`
- 💜팀장 : 박성은
- 🧡팀원 : 권은혜
- 💛팀원 : 박효찬(형상관리자)
- 💚팀원 : 지동현

## ⚙️ `개발 환경`
- FRONT  
     <img alt="Html" src="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white">  
    <img alt="Css" src="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white">  
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?&style=for-the-badge&logo=JavaScript&logoColor=black">  
    <img alt="Redux" src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white">

- BACK  
     <img alt="Java" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white">  
    <img alt="Spring" src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">  
    <img alt="SpringBoot" src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">  
    <img alt="SpringSecurity" src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=pink">

- DATA  
     <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">

- communication  
     <img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white"/><img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"/>

## 💻 ...
<a href = "https://github.com/ChungChun-university/DoognDoogn.git"><img alt="GitHub" src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/></a> 

## 📂 `패키지구조(Artifact)` 
❗ <백엔드 패키지 구조> ❗
```
- main
│  ├─java
│  │  └─com
│  │      └─rocket
│  │          └─healingpets
│  │              ├─auth
│  │              │  ├─filter
│  │              │  ├─handler
│  │              │  └─service
│  │              ├─common
│  │              ├─config
│  │              ├─etc
│  │              ├─hospitals
│  │              │  ├─controller
│  │              │  ├─model
│  │              │  │  ├─dto
│  │              │  │  │  ├─ClinicType
│  │              │  │  │  ├─Hospital
│  │              │  │  │  └─HospitalSchedule
│  │              │  │  └─entity
│  │              │  ├─repository
│  │              │  └─service
│  │              ├─Reservations
│  │              │  ├─controller
│  │              │  ├─model
│  │              │  │  ├─dto
│  │              │  │  └─entity
│  │              │  ├─repository
│  │              │  └─service
│  │              ├─reviews
│  │              │  ├─controller
│  │              │  ├─model
│  │              │  │  ├─dto
│  │              │  │  └─entity
│  │              │  ├─repository
│  │              │  └─service
│  │              ├─test
│  │              │  └─controller
│  │              ├─users
│  │              │  ├─controller
│  │              │  ├─model
│  │              │  │  ├─dto
│  │              │  │  └─entitiy
│  │              │  ├─repository
│  │              │  └─service
│  │              └─util
│  └─resources
│      └─static
│          ├─img
│          │  └─hospital
│          │      ├─info
│          │      └─owner
│          └─uploads
└─test
    └─java
        └─com
            └─rocket
                └─healingpets

❗ <프론트 패키지 구조> ❗

src
│  App.js
│  index.js
│  Store.js
│
├─api
│      AdminAPICalls.js
│      Apis.js
│      HospitalAPICalls.js
│      ReservationAPICalls.js
│      ReviewAPICalls.js
│      UserAPICalls.js
│
├─components
│  ├─commons
│  │  │  AlertMessage1.js
│  │  │  Footer.js
│  │  │  Header.js
│  │  │  Navbar.js
│  │  │
│  │  ├─footer
│  │  │      Footer.js
│  │  │
│  │  └─header
│  │          AdminHeader.js
│  │          HosHeader.js
│  │          UserHeader.js
│  │
│  └─lists
│          HospitalList.js
│
├─css
│  │  AdminMain.css
│  │  AllReviews.css
│  │  ClinicHistory.css
│  │  Expenses.css
│  │  HosAdminMain.css
│  │  HosDetails.css
│  │  HosInfo.css
│  │  HospitalList.css
│  │  HospitalView.css
│  │  HosReser.css
│  │  Layout.css
│  │  Main.css
│  │  MyReviews.css
│  │  ReserPage.css
│  │  ReserStatus.css
│  │  Signup.css
│  │  UserMain.css
│  │
│  ├─admin
│  │      HosControl.css
│  │      ReserControl.css
│  │      ReviewControl.css
│  │      UserControl.css
│  │
│  ├─component
│  │      AdminHeader.css
│  │      AlertMessage1.css
│  │      Footer.css
│  │      Header.css
│  │      HosHeader.css
│  │      MyPage.css
│  │      UserHeader.css
│  │
│  ├─hosAdmin
│  │      HosReserControl.css
│  │      HosReviewControl.css
│  │      HosSchedule.css
│  │
│  └─user
│          ChangePWD.css
│          FindID.css
│          Login.css
│
├─data
│      Hospital.json
│
├─fonts
│      GmarketSansTTFBold.ttf
│      GmarketSansTTFLight.ttf
│      GmarketSansTTFMedium.ttf
│      KNPSKkomi.otf
│
├─layouts
│      AdminLayout.js
│      FooterLayout.js
│      HosLayout.js
│      Layout.js
│      MyPageLayout.js
│      UserLayout.js
│      UserLayout2.js
│
├─modules
│      HospitalModule.js
│      HospitalScheduleModule.js
│      index.js
│      ReservationModule.js
│      ReviewModule.js
│      UserModule.js
│
└─pages
    │  AdminMain.js
    │  ChangePw.js
    │  HosAdminMain.js
    │  LoginForm.js
    │  Main.js
    │  UserMain.js
    │
    ├─admin
    │      HosControl.js
    │      ReportsControl.js
    │      ReserControl.js
    │      ReviewControl.js
    │      UserControl.js
    │
    ├─hosadmin
    │      HosInfo.js
    │      HosReserControl.js
    │      HosReviewControl.js
    │      HosSchedule.js
    │
    ├─hospital
    │      AllReviews.js
    │      HosDetails.js
    │      HospitalView.js
    │      HosReser.js
    │
    ├─mypage
    │      ClinicHistory.js
    │      MyInfo.js
    │      MyPet.js
    │      MyReviews.js
    │      ReserStatus.js
    │
    ├─reservations
    │      BeautyReserPage.js
    │      ReserPage.js
    │
    └─user
            ChangePWD.js
            Expenses.js
            FindID.js
            Login.js
            Logout.js
            Signup.js
```

<h2>📌 주요 기능</h2>
<p>
<h3> 사용자 </h3>
 📌 로그인 (로그인, 아이디 찾기, 비밀번호 찾기) <br>
 📌 회원가입  - 회원 등록  (아이디 중복 확인, 닉네임 중복 확인, 비밀번호 확인, 이메일 인증), 펫 정보 입력 <br>
                  - 병원 등록  (아이디 중복 확인, 닉네임 중복 확인, 비밀번호 확인, 이메일 인증), 병원 정보 입력 <br>
 📌 마이페이지 - 내 정보( 회원 정보 조회, 닉네임 수정, 이메일 수정, 전화번호 수정, 비밀번호 수정) <br>
                      예약 현황 ( 예약 현황 조회, 예약 취소  )
                      진료 기록 ( 진료 기록 조회, 리뷰 쓰기 )
                      나의 후기 ( 후기 조회, 후기 삭제)
                      마이 펫 ( 펫 정보 조회, 펫 등록, 펫 정보 수정, 펫 정보 삭제 ) 
 📌  병원검색 - 등록된 병원 조회, 등록된 병원 상세 조회, 병원 단일 조회<br> 
 📌  병원예약 - 등록된 병원의 위치를 실제 지도를 통해서 알 수 있다.
	      - 위치를 클릭하면 그 병원의 상세페이지로 이동해 예약이 가능하다.
              - 예약은 캘린더로 날짜 지정후 자동으로 회원의 등록된 펫 정보를 불러와서 예약 할 수 있다. <br> 
 📌  후기보기 - 각 병원의 후기 조회 <br>
</p>
<p>
<h3> 병원 관리자 <h3>
 📌 예약관리 - 예약 현황 (병원의 예약 정보 조회, 병원의 일정에 따라 예약 취소후 취소 사유를 입력해 예약한 사용자에게 전달 ) <br>
 📌 후기관리 - 후기 조회 ( 병원을 이용한 사용자들의 후기 조회)<br>
 📌 일정관리 - 병원 일정 관리( 캘린더를 통해 휴진일, 예약 가능 시간 관리)<br>
 📌 마이페이지 - 병원 정보 ( 등록된 자신의 병원정보 조회, 수정이 가능하다. ) <br>
</p>
<p>
<h3> 관리자 </h3>
 📌 병원관리 - 병원 관리 (등록된 병원 정보 조회, 등록된 병원 정보 수정, 등록된 병원 삭제)   <br>
 📌 예약관리 - 예약 현황 ( 각 병원의 예약 정보를 조회 ( 유형(진료, 수술, 미용), 아이디로 개별 조회 가능) )<br>
 📌 후기관리 - 일반 후기 ( 각 병원의 작성된 후기 조회(클린봇으로 비속어 처리 가능))<br>
 📌 회원관리 - 회원 목록 (등록된 회원 조회, 등록된 회원 삭제(DB에 삭제되는 것이 아니라 상태는 변경해서 그 회원이 로그인하면 탈퇴된 회원이라고 알림창이 나온다.) <br>
</p>

## 🗣️ 후기

>## 지동현
> - 소감
><br> 이번 프로젝트를 하면서 스프링 시큐리티, 엔티티, jwt 등에 대해서 폭넓은 이해를 할 수 있었다. Front에서는 리듀서로 리덕스 상태를 관리하여 api호출을 통해 데이터가 변경 또는 생성됨에 따라 리듀서 액션 함수를 통해 state 변경이 이루어져 자연스럽게 화면이 렌더링 될 수 있도록 했던 점에서 만족스러웠다. 그리고 Back에서 데이터를 불러오기 위해 Fetch 메서드 대신 Axios를 사용하여 기본적으로 request를 보낼때 헤더에 토큰을 담고 request body가 필요한 경우 파라미터에 담아 보낼 수 있도록 form을 생성하여 api를 좀 더 원활하게 호출할 수 있았던 것 같다.
><br><br>
>- 아쉬운점
<br>사실 후회가 없을만큼 시간을 투자하기도 했고 제가 맡았던 태스크에 있어서는 코드에 대해 거의 모두 설명할 수 있을 정도로 이해도가 높았기 때문에 크게 아쉬운 점이 없었던 것 같습니다. 다만, 프로젝트 후반부에서 각자의 브랜치에서 작업한 것을 통합하는 과정에서 매끄럽게 반영이 되지 않아 당황스러웠습니다. 그래서 컴포넌트 스타일을 작성할 때  className을 더 구체적으로 작성한다던가 작업한 브랜치에서 한꺼번에 많은 내용을 한 커밋에 담기보다는 task를 구체적으로 나누어 여러번 커밋하는 해야하는 필요성을 느낄 수 있게 된 것 같습니다.

<br>

>## 박성은 
> - 소감
><br> 처음으로 제대로 진행한 프로젝트였고 프로젝트를 기획하고 설계하는 과정에서 팀원들과의 소통이 잘 이루어진 것 같아 프로젝트 진행 동안 큰 문제없이 프로젝트를 마칠 수 있었던 것 같다. 팀원 전부 서로 의견을 내며 프로젝트에 적극적으로 임하며 맡은 일을 해내는 모습이 팀워크가 좋다고 느꼈다. 프론트와 백을 연동하는 과정에서 어려움이 많았지만 시작 전에는 어떻게 연동이 되는 건가 하고 막막했지만 이제는 그 흐름을 알 수 있게 되었고 어떤 방향으로 진행되는지도 더 확실하게 이해할 수 있는 시간이었다. 
><br><br>
>- 개선할 점 및 아쉬운 점
<br>연관된 리듀서들은 통합해서 관리하지 않으면 데이터 흐름을 추적하고 유지하는데 어려움이 생길 수 있고 한 리듀서의 상태 변화가 다른 리듀서에 영향을 줄 경우,  관리하는 것이 더 어렵다. 또한, 각 모듈이 분리되어 있으면 팀원들이 관련된 상태나 로직을 찾는 데 혼란을 겪을 수 있다는 것을 이미 각각의 리듀서를 만들고 마무리한 상태에서 알게 되어 계속 오류가 생기고 어려움이 많아서 처음에 잘 모르고 만든 것을 후회했다. 또한 필요한 내용들이 다 다른데 DTO를 새로 만들지 않고 팀원들끼리 서로 쓰다보니 계속 오류가 나고 되던 기능이 안 되는 게 계속 보여서 아쉬웠다.

>## 박효찬 
> - 소감
><br> 실제로 이런 프로젝트를 하게 되면서 어떻게 작업을 해야 하는지 작업 방향성에 대해 알 수 있어고, 실제로 작업하다
        여러 문제들이 발생했는데 이런것들을 해결하는 과정이 좋았고, 구현하는 기간이 부족해서 자신이 원하는 
        기능을  제대로 구현하지 못한점, 발표 전날에 종합하는 과정에서 오류가 발생해 각자 만들었던
        기능이 제대로 수행하지 못해서 늦게 까지 남아서 수정했던 이런 과정들이 한편으로는 아쉬었지만 다른 한편으로는
        이러한 경험을 해서 나중에는 어떻게 작업해야 할지 개선할 수 있는 경험을 했던거 같습니다.
><br><br>
>- 개선할 점 및 아쉬운 점
<br>백에서 작업할 때 조회, 생성 ,수정 기능별로 DTO를 생성하는데 이걸 하나의 폴더로 생성해서 어떤 
        기능의 어떤 DTO를 써야 하는지 한눈에 파악하기 힘들었다.
               작업을 할 때 주석을 처리해서 어떤 기능을 수행하는지 명시 했지만 이걸 동작 순서로 정리하면 
               쉽게 파악 할 수 있었는데 그것을 못한점, 
       프론트에서 이미지 파일을 올려서 서버에 저장하려고 할 때 딜레이가 걸려서 실제로 프로트에서
               이미지를 조회할려고 하면 시간이 거렸다.
               여러사람들이 공통된 기능에서 작업을 하다보니 실제로 종합하는 과정에서 자신은 백에서 이렇게 
               적용했는데 다른사람은 다르게 작성해서 기능이 작동하지 못한 문제가 발생했다.

<br>

>## 권은혜 
> - 소감
><br> 세미 프로젝트를 진행하며 여러가지 기능을 새롭게 사용해볼 수 있어서 좋았고, 팀 단합이 잘 돼 끝까지 포기하지 않고 프로젝트를 완수할 수 있어서 감사했다. 
useSelector를 사용하며 리엑트 리덕스에 대해 조금 더 알게 됐고, chat gpt를 복사 붙여넣기 하는 것에서 넘어 코드의 흐름을 보게 됐다. 
브랜치 규칙을 잘 지켜, 오류가 발생했을 때 돌아가서 다시 확인할 수 있어서 좋았지만, 각자의 작업영역에 필요한 부분에 맞게 DTO, service, controller를 변경하는 작업에서 세밀한 소통이 이루어지지 않았고, 내 작업에 맞게 새로운 작업영역을 설정하지 않고 메인을 변경하다 보니 많은 충돌이 발생했다. 
앞으로 작업할 때에는 나와 동일하게 작업 영역을 사용하는 팀원과 세밀하게 소통하며 각자의 작업에 맞는 작업 영역 설정을 새롭게 해줘야겠다고 생각했다. 
끝까지 많은 오류가 발생해 당황했지만, 어느 부분에 오류가 발생하는지 확인하고 함께 고쳐나가는 작업을 통해 끝까지 프로젝트에 몰입하며 완성해나가는 부분에 매력을 알게된 것 같다.
 

## 힐링펫츠 웹 스크린 구성 및 기능

| **Home(ADMIN)** |  **Home(HospitalADMIN)**  |  **Home(User)** |
| :---:|:---:|:---:|
| <img align="center" alt="메인" src="../img/관리자-메인.png" width="240px" /> | <img align="center" alt="로그인" src="../img/병원관리자-메인.png" width="240px" /> | <img align="center" alt="회원가입" src="../img/비회원-메인.png" width="240px" /> |

| **로그인** |  **회원가입**  |  **병원관리자-일정관리** |
| :---:|:---:|:---:|
| <img align="center" alt="ID찾기" src="../img/로그인.png" width="240px" /> | <img align="center" alt="공지사항" src="../img/회원가입.png" width="240px" /> | <img align="center" alt="게시판" src="../img/병원관리자-일정관리.png" width="240px" /> |

| **병원검색** |  **병원예약**  |  **MyPage** |
| :---:|:---:|:---:|
| <img align="center" alt="강의" src="../img/병원검색.png" width="240px" /> | <img align="center" alt="나의수강" src="../img/병원예약2.png" width="240px" /> | <img align="center" alt="마이페이지" src="../img/회원-마이페이지.png" width="240px" /> |
