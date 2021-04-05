# sm_week05
스마트모바일프로그램설계 5주차   

4주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week04

### 팀 구성   
스마트정보통신공학과 201621216 이준석   
스마트정보통신공학과 201921036 김경진   
스마트정보통신공학과 201921054 박유리   
스마트정보통신공학과 201921083 이혜정   
스마트정보통신공학과 201921104 홍수빈    
스마트정보통신공학과 201990009 미르자크메더브 사르더르    

   ***   
### 모든 항목은 변경되거나 삭제될 여지가 있습니다   
   ***   

### (1) 화면 구성   

이번 주차에는 저번 3주차에 카카오오븐으로 대략적으로 디자인했던 앱의 화면 구성을 안드로이드 스튜디오에서 다시금 재구성하기로 하였습니다.   
아직은 화면 구성만 하는 단계여서 자세한 기능은 천천히 구현할 예정입니다.   

#### 로그인 및 회원가입   
>진행과정1   
>[로그인 버튼 오류 영상](https://user-images.githubusercontent.com/57963888/113570612-ae8d2300-964f-11eb-8f60-1ff293280433.mp4 "새탭에서 동영상 재생")   
>디자인만 재구성하여 화면을 만들었는데 버튼을 누르면 로그인 버튼이 이동하는 오류가 있었습니다.   
>휴대폰에서 앱이 눈에 띌 수 있게 아이콘을 변경해주었습니다.
>또한, 앱의 배경화면을 제작하여 앱이 시작할 때 띄워줄 수 있도록 설정해주었습니다.

>진행과정2   
>![KakaoTalk_20210405_030026351](https://user-images.githubusercontent.com/57963888/113570576-9d441680-964f-11eb-8eab-9343d22cf074.png)
>![KakaoTalk_20210405_030103244](https://user-images.githubusercontent.com/57963888/113570636-b351d700-964f-11eb-982c-82081ef27bbc.png)   
>[로그인 버튼 고침 영상](https://user-images.githubusercontent.com/57963888/113570637-b5b43100-964f-11eb-9ebb-21628dc73342.mp4 "새탭에서 동영상 재생")   
>레이아웃을 잘못 설정하여 생긴 오류로, 레이아웃을 다시금 조정해주었습니다.   
>두 번째 사진과 같이 고쳐주니 로그인 버튼이 이동하는 버그를 수정할 수 있었습니다.   
>또한, 스플래쉬, 회원가입, 로그인, 메인 엑티비티랑 레이아웃을 만들어서 화면 간의 이동을 쉽게 만들었습니다.   
>버튼 클릭에 따라 다른 화면을 불러올 수 있으며 
>>(activity_login) 로그인 버튼 -> activity_main(레이아웃)   
>>(activity_login) 회원가입 ->  activity_join(레이아웃)   
>>(activity_join) 가입 버튼 -> activity_login(레이아웃)   


#### 게시판
>진행과정
>![KakaoTalk_20210405_204211429](https://user-images.githubusercontent.com/57963888/113571363-39225200-9651-11eb-9cde-ee700d112580.png)   
>음식점에 관한 게시판을 만들었습니다.
>자신이 갔던 곳이 얼마나 좋았는지, 짧은 코멘트와 별점 제도로 음식점에 대해 후기를 남길 수 있습니다.
