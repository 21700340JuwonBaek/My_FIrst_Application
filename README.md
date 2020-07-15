# My_FIrst_Application

## 7월 15일 금요일 수업시작

모바일쪽으로 가려면.... 주언어 하나 하고 안드로이드 뭐 그런거 할 수 있게끔 할것.
물리적인 연결을 해서 하는 편이 더 빠르다.

엑티비티 : 애플리케이션을 시작할 때에 나타나는 레이아웃.

Name : 앱 이름

Package Name : 구글 플레이 올라가는 이름

Minimum SDK : 돌아갈 수 있는 최소 OS사양

graddle : 검색해보기(자동으로 필요한 라이브러리를 인터넷으로 받아주는 느낌)




### 앱의 구성요소

manifest : 안드로이드 앱을 구성하고 있는 명세서 느낌. Permission(권한)을 요구하는 명령어들... 

액티비티의 정보가 있음.메니페스트에 있는 액티비티의 이름과 자바폴더에 있는 엑티비티의 이름이 동일해야 함.
intnet - filter : 가장 먼저 나오는 엑티비티 


### 앱의 실행
onCreate : 구동할 때에 가장 먼저 실행되는 메소드

Sync project with Graddle Files : 내 컴퓨터와 핸드폰에 라이브러리 동기화 하기.
bulid graddle에다가 라이브러리 추가하기.

이미지 추가시에는..
res-drawable에 이미지 넣기. 다만 이름은 영어소문자 + 이름 + _ 만 써야함.

메인 엑티비티 실행 -> 여기에서 onCreate실행함.


### 이벤트처리
이벤트를 만들기 위해서는 사용하려는 레이아웃에 아이디를 만들어야 한다.
res->layout에서 텍스트뷰에
        android:id="@+id/tv1" ==> 아이디를 tv1으로 만든다.


### 패딩 마진?


### 이미지 붙여넣기

### 라이브러리 추가하는법

파일--> ProjectStructure-->Dependency-->app --> + 입력하면
graddle --> buildgraddle에 자동으로 library implements
