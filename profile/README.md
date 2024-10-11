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

