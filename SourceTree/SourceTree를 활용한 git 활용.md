#SourceTree를 이용한 git 활용법
## Clone
 **new repositories**를 생성하여 Github의 원격 저장소와 내 컴퓨터의 로컬 저장소를 연동하는 작업.
 
 1. [Github 홈페이지](http://github.com/)에 들어가 로그인을 한다.
 2. **New repsitories**를 클릭한다.
 3. **Repository name**과 **Description**작성하고 **Public/Private**여부 등을 설정한 후 **Create repository**를 클릭한다.
 4. **SourceTree**를 실행하여 다음과 같이 **복제/생성**을 클릭한다.
  ![](http://i.imgur.com/XBFmJe5.png "title" "width:500px;")

 5. 다음 화면이 나오면 **소스경로 / URL**에 **Github**홈폐이지에서 생성했던 **repository**의 URL을 집어 넣는다.
  ![](http://i.imgur.com/LvzPUmd.png "title" "width:500px;")
  그리고 **목적지 경로**를 **빈 폴더**로 설정해준 후 **클론**을 클릭한다.

## Commit
  **Clone**이 완료되어 **로컬 저장소**와 **원격 저장소**가 연동이 된 경우 **Commit**을 통해 작업한 내용을 로컬저장소에 기록하는 과정. 각 과정 마다 "버그 수정", "기능 추가" 등의 **comment** 를 적을 수 있다. 

 1. **SourceTree**를 실행하여 생성된 저장소를 클릭하고 다음과 같이 **커밋**을 클릭한다.
  ![](http://i.imgur.com/QBaNUOM.png "title" "width:500px;")
  
 2. 다음 화면이 나오면 **stage All**을 클릭하고 **comment**를 작성한 후 우측 하단의 **커밋**을 클릭한다.
  ![](http://i.imgur.com/NG4gK0L.png "title" "width:500px;")

## Push
  **Commit**을 통하여 **로컬 저장소**에 기록된 내용 중 **원격 저장소**에 반영 되지않은 커밋을 원격저장소로 보내는 과정.

 1. **SourceTree**를 실행하여 **push**를 하고자하는 저장소를 클릭하고 다음과 같이 **푸시**를 클릭한다.
  ![](http://i.imgur.com/uEa8Uki.png "title" "width:500px;")
  
 2. 다음 화면이 나오면 **모두선택**을 체크하고 우측 하단의 **푸시**를 클릭한다.
  ![](http://i.imgur.com/xJh1fO8.png "title" "width:500px;")