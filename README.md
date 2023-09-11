# 📱 MODA
### 유튜브 영상 스트리밍 앱
<br><br>

## 📋 프로젝트 소개

#### MODA는 youtubeAPI를 이용하여 영상을 볼 수 있는 앱입니다.
#### 유저는 로그인화면에서 회원가입을 진행하고 로그인하여 유튜브 인기 동영상을 볼 수 있으며, 검색어를 입력하여 연관 동영상을 확인 할 수 있습니다.
#### 또한, 마이페이지에서 나의정보를 확인하고 수정, 로그아웃등을 이용할 수 있습니다.
#### 이 앱은 스토리보드를 사용하지 않고 MVC패턴을 채용하여 코드로 UI를 구성하였으며, Swift 언어와 Xcode 개발환경을 사용하여 개발되었습니다.

<br><br>
- - -
## 🛠️ 사용한 기술 스택 (Tech Stack)
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
- - -

<br><br>
- - -
## 🗓️ 개발 기간
* 2023-09-04(월) ~ 2023-09-08(금), 5일간
- - -
<br><br>

## 📌 주요 기능

* 		로그인 화면
    * 회원가입과 로그인을 수행하는 화면입니다.
    * 유저는 회원가입을 통해 ID, PW, Email등을 입력하고 가입할 수 있습니다.
    * 유저의 데이터는 CoreData를 이용하여 저장, 관리 됩니다.
    * 회원가입을 완료한 유저는 가입당시 입력했던 ID와 PW를 입력하고 앱은 CoreData에서 데이터 일치여부를 확인한 후 메인화면으로 이동합니다.
* 		메인 화면
    * youtubeAPI를 이용하여 인기동영상을 가져와서 보여줍니다.
    * 화면을 아래로 당겨서 영상을 새로고침하여 새로운 영상을 불러올 수 있습니다.
    * 무한스크롤 기능을 지원하여 유저가 스크롤을 내릴 시 더 많은 영상들을 불러와서 보여줍니다.
    * 검색기능을 통하여 검색어를 입력하고 관련 영상의 목록을 보여주는 검색화면으로 이동합니다.
    * 썸네일을 탭 할시 상세화면으로 이동합니다.
* 		검색 화면
    * 검색된 영상들을 보여주는 화면입니다.
    * 무한스크롤 기능을 지원하여 유저가 스크롤을 내릴 시 더 많은 영상들을 불러와서 보여줍니다.
    * 썸네일을 탭 할시 상세화면으로 이동합니다.
* 		상세 화면
    * 영상을 재생할 수 있는 화면입니다.
    * 전체화면으로 영상을 재생하거나 youtube버튼을 눌러 해당 영상의 주소로 이동이 가능합니다.
* 		마이페이지
    * 유저의 Name, ID, PW, Email등과 같은 정보를 보여줍니다.
    * Edit버튼을 통해서 유저의 정보를 수정하고 저장할 수 있습니다.
    * 로그아웃 버튼을 이용하여 다른 ID로 재로그인이 가능합니다.

- - -
