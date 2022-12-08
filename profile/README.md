![header](https://capsule-render.vercel.app/api?type=egg&color=auto&height=200&section=header&text=WATCHVIE%20&fontSize=60)



# About the Project 🎬 - WATCHVIE
Watch Movie의 줄임말로 무료 영화 API를 이용한 영화 정보를 제공하는 웹 페이지입니다.
영화 제목, 장르, 개봉일, 인기도 등의 정보를 제공합니다.

#### contents
- [Team Member](#1-team-member)<br/>
- [Getting Start](#2-installation)<br/>
- [Project Architecture](#3-project-architecture)<br/>
- [Usage](#4-usage)<br/>
- [Roadmap](#5-roadmap)<br/>
- [Contributing](#6-contributing)<br/>
- [Environment](#7-environment)<br/>
- [Convention](#8-convention)<br/>
- [License](#9-license)<br/>



# 1 Team Member  
팀원의 역할과 컨택가능한 메일 주소입니다. 

#### FullStack 
이동현 - dhl9810@khu.ac.kr <br/>
김담인 - ekadls757@khu.ac.kr <br/>

#### Backend  
루 창 - luchang@khu.ac.kr <br/>
홍승표 - zackinthebox@khu.ac.kr<br/>

#### Frontend 
고윤성 - reallystars@khu.ac.kr <br/>
조예린 - dpfls5645@khu.ac.kr <br/>






# 2 Installation
저희의 프로젝트를 시작해보세요.









# 3 Project Architecture
<br/>





# 4 Usage 
주요 기능 소개
- Home page
![homepage](https://user-images.githubusercontent.com/114723339/206430229-55726f15-00e6-49df-b8de-2b1d7d475684.jpeg)<br/>
메인 페이지에서 인기있는 영화 목록을 보여줍니다. <br/>
옵션(1) 상단의 내비게이션 바에서 5가지 장르 중 맘에 드는 장르를 선택합니다.<br/>
옵션(2) 상단의 내비게이션 바 우측의 로그인 및 회원가입 버튼으로 WATCHVIE에 사용자 정보를 등록할 수 있습니다. <br/>
옵션(3) 이미 로그인이 되어있는 경우 로그아웃하면 메인화면으로 돌아갑니다.<br/>
옵션(4) 영화에 대한 정보를 검색하여 확인해볼 수 있습니다.<br/>
<br/>

- SignUp page
![signuppage](https://user-images.githubusercontent.com/114723339/206430239-d55a003c-d17c-4653-acd8-3fd6b89e55e0.jpeg) <br/>
homepage에서 옵션(2)의 SingUp버튼을 누르면 위 화면으로 이동합니다.<br/>
이메일,이름,ID,PW(password)를 입력하여 회원가입 절차를 진행합니다. <br/>
화면 하단의 SignUp 버튼을 누르면 SignIn page로 넘어갑니다.<br/>

- SignIn page
![loginpage](https://user-images.githubusercontent.com/114723339/206430248-c534ab34-109b-48ce-8738-54b3bd5f828b.jpeg)<br/>
homepage에서 옵션(2)의 SignIn버튼을 누르면 위 화면으로 이동합니다. <br/>
UserID와 PW를 입력하고 하단의 SignIn 버튼을 눌러 페이지에 로그인합니다. <br/>
<br/>



# 5 Roadmap
#### Frontend
1️⃣ 장르 선택 및 로그인/회원가입으로 구성된 헤더 구현 <br/>
2️⃣ 로그인, 회원가입, 영화 정보 등 단일 페이지 구성 <br/>
3️⃣ 각 페이지들 라우팅 <br/>
4️⃣ 영화 API 연결 <br/>
5️⃣ Backend - Frontend 연결 <br/>
6️⃣ css 정리 <br/>


#### Backend

<br/>



#### 공통
7️⃣ AWS 배포 








<br/>
# 6 Contributing
프로젝트에 기여하고 싶으신 분들은 아래 절차를 따라주시기 바랍니다.

    1. 프로젝트 fork
    2. feature branch 생성 (git checkout -b feature/name)
    3. commit (git commit -m "Add feature)
    4. push (git push origin feature/name)
    5. pull request 생성
    
    Pull request는 최대한 빨리 확인하도록 하겠습니다. 
    
pull request 포함 문의사항은 📧[contact](#1-team-member)  으로 연락 부탁드립니다.
<br/>
<br/>

# 7 Environment
- Language <br/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=black"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=black">
- Programming <br/> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=black"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white">
- Library <br/> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/React Router-CA4245?style=for-the-badge&logo=React Router&logoColor=black"> 
<br/>
<br/>






# 8 Convention
#### Commit Convention
- [Conventional Commit](https://www.conventionalcommits.org/ko/v1.0.0/#%ea%b7%9c%ea%b2%a9)

- [Commit msg](https://medium.com/humanscape-tech/%ED%9A%A8%EC%9C%A8%EC%A0%81%EC%9D%B8-commit-message-%EC%9E%91%EC%84%B1%EC%9D%84-%EC%9C%84%ED%95%9C-conventional-commits-ae885898e754)
![image](https://user-images.githubusercontent.com/114723339/206160359-4cbfbdaa-4ca1-4197-a784-b091d7b11687.png)
commit의 종류는 위와 같이 구분합니다.

#### Work Flow
1. ISSUE 생성<br/>
작업에 대한 정보를 포함한 ISSUE를 생성합니다. <br/>
2. 생성된 ISSUE에 대해 Draft PR 생성<br/>
ISSUE를 연결하여 관리하고 Pair Programming을 어느정도 진행하기 위해 Draft PR을 생성합니다. <br/>
3. 작업을 마친후 PR Open 및 코드 리뷰<br/>
작업이 끝나게 되면 Draft PR을 일반 PR로 변경하고 서로 코드 리뷰를 진행합니다.<br/>
4. Merge & PR Close & Remove Branch<br/>
코드 리뷰까지 모두 마리가 되면 해당 브런치를 dev에 merge하고 pr 닫기 및 브런치 삭제를 진행합니다.<br/>
<br/>

# 9 License

