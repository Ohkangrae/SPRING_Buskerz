# ✔SPRING_Buskerz✔ 
Buskers 스프링 프로젝트 By 일조가일냈조
<br><br>
✨Bukserz 기획의도 및 배경
- 길거리의 아티스트와 시민을 연결짓는 버스킹 정보 공유 플랫폼 <br>
"길거리의 모든 춤과 음악, 그리고 예술" <br>
누구나 아티스트가 될 수 있고 자신만의 버스킹을 홍보한다. <br>
✨개발 기간 : 2주 <br>
----------------------------------------------------------------------------------------------------------------------
✨나의 작업<br>
🎈[Front-end]<br>

헤더, 푸터<br>
1. 'Yes24티켓' 헤더, 푸터를 벤치마킹하여 제작하였습니다.<br>
2. Thymeleaf를 이용하여 모든페이지에  연결하였습니다.<br>
<br>
메인 페이지<br>
1. 'Yes24티켓' 메인페이지를 벤치마킹하여 제작하였습니다.<br>
2. ajax를 이용하여 새로고침 없이 데이터를 변경하는 기능을 구현 하였습니다.<br>
<img src="https://user-images.githubusercontent.com/98381603/182021541-a1ddc863-a8fe-4adb-b687-9a556b0954e5.gif" width="100%"><br>

모집공고 페이지, 모집공고 상세보기 페이지<br>
1. 'Yes24티켓' 공지사항 페이지를 벤치마킹하여 제작하였습니다.<br>
2. js를 이용하여 스크롤 맨위로 이동할 수 있는 버튼을 구현하였습니다.<br>
<br>
<img src="https://user-images.githubusercontent.com/98381603/182082324-22224dc0-b717-4450-b4ca-7be77eabb247.gif" width="100%"><br>

-----------------------------------------------------------------------------------------------
✨나의 작업<br>
🎈[Back-end]
랭킹페이지 <br>
1. 'Yes24' 랭킹페이지를 벤치마킹하였으며 팀 의도와 맞게 전체, 뮤지션, 퍼포먼스 카테고리로 나누어 제작하였습니다.<br>
2. ARTIST_TYPE 이라는 컬럼을 만들어서 뮤지션과 퍼포먼스를 나누었습니다.<br>
3. 좋아요 순으로 나열을 하는 쿼리를 작성하여 15위까지 보여지도록 구현하였습니다.<br>

<img src="https://user-images.githubusercontent.com/98381603/182128361-6bd801c3-6b9f-4470-a941-bdd13d2c1ead.gif" width="100%"><br>
------------------------------------------------------------------------------------------------------------------------------------------------------------
🎈프로젝트 전체적인 타임라인 <br>
|일자|내용|구체적인 활동|
|:---------:|:--------:|:-------:|
|5월 31일 ~ 6월 1일|주제 선정|주제 선정|
|6월 2일 ~ 6월 6일|설계|메뉴트리 작성, ERD 설계|
|6월 7일 ~ 6월 17일|설계, Front 작업|프론트엔드 역할 분담 및 프론트 작업|
|6월 14일 ~ 6월 16일|설계|백엔드 사전 설계 작업|
|6월 17일 ~ 6월 29일|Back 작업|백엔드 역할 분담 및 백 작업|
-------------------------------------------------------------------------------------------------------------------------------------------------------------
🎈나의 프로젝트 타임라인<br>
|일자|담당 파트|작업 내용|
|:---------:|:--------:|:-----------:|
|6월 7일 ~ 6월 9일|Front-end|헤더, 푸터 작업 및 전체 페이지 연결|
|6월 7일 ~ 6월 9일|Front-end|메인페이지 전체적인 레이아웃 잡기|
|6월 9일 ~ 6월 11일|Front-end|메인페이지 레이아웃 완료, css 작업|
|6월 12일 ~ 6월 16일|Front-end|모집공고페이지 벤치마킹 및 css작업|
|6월 17일|Front-end|모집공고 상세보기 페이지 벤치마킹 및 css작업|
|6월 17일 ~ 6월 19일|Back-end|랭킹페이지 관련 Mapper 쿼리 작성 및 테스트|
|6월 20일 ~ 6월 21일|Back-end|동적쿼리 작성 및 에러 수정|
|6월 23일 ~ 6월 25일|Back-end|프론트단 일부 수정, Mapper 쿼리 수정|
|6월 26일 ~ 6월 27일|Back-end|아티스트 더미데이터 생성 및 공유|
|6월 27일 ~ 6월 29일|Back-end|세세한 버그 수정|
|6월 30일|Back-end|마무리 작업|
-------------------------------------------------------------------------------------
✨프로젝트를 진행하면서 느낀 점<br>
첫 프로젝트였던 jsp프로젝트 때 보다는 팀원들 모두 협업에 대한 중요성도 알았기 때문에 조금은 수월했습니다.
로컬에서 작업 -> 개인 원격 저장소 push -> 공용 저장소로 pr -> pull의 원리를 제대로 이해하고 팀원들 간 병합 충돌을 최소화하기 위해서 각자 무엇을 하고 있는지 Slack을 통하여 계속 공유하니 저번 프로젝트보다 병합 충돌도 많이 줄었고 마지막에 프로젝트를 합칠 때도 저번에 비하면 아주 적은 시간만 소모할 수 있었습니다. 소통과 협업 도구에 익숙해지는 것의 중요성을 깨달았습니다.<br>
REST API를 RESTful하게 사용하기 위해 여러가지 HTTP 메서드를 활용하였으며 SPRING 수업을 들으면서 확실하게 잡히지 않았던 개념들을 복습하고 활용해볼 수 있는 의미있는 시간이었다. <br>
또한 만족스럽지만 서버 배포까지는 가지 못했고 나중에 기회가 된다면 정식으로 배포해보는 기회가 있었으면 좋겠다고 생각했다.
