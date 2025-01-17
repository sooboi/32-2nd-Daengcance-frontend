[![Video Label](http://img.youtube.com/vi/S6aS-q1nbnk/0.jpg)](https://youtu.be/S6aS-q1nbnk)



# 1. 팀 소개

![img](https://user-images.githubusercontent.com/103011139/169689069-28dab5c0-42d5-412c-a727-8041e04c51da.png)
![다운로드](https://user-images.githubusercontent.com/103011139/169689112-a0fee648-a403-4260-b075-1aef61158b98.jpeg)

팀명 : 댕캉스(Daengcance)
<br><br>
팀원
<br>
BE : 최지수, 윤진섭
<br>
FE : 이수광(PM), 유동혁, 이현정, 장형원

진행 기간 : 2022.05.09 ~ 2022.05.20
<br><br>

# 2. 서비스 소개

반려견 돌봄 예약 사이트
<br>

## 2-1. 메인 서비스 소개

1. 날짜 캘린더로 원하는 기간동안 예약이 가능합니다.
2. 원하는 조건의 펫시어터를 고용할 수 있습니다.
3. 펫시어터의 장소를 보고 확인할 수 있습니다.
4. 펫시어터의 리뷰 목록을 확인하고 상세 내용을 확인할 수 있습니다.
5. 예약 후 마이페이지에서 예약내용을 할 수 있습니다.
   <br>

# 3. 필수 구현사항

1. 회원가입, 로그인(소셜 로그인)
2. 메인 페이지 (날짜 캘린더, 조건 선택 예약)
3. 지도 API
4. 리뷰기능
   <br>

# 4. 추가 구현사항

1. 이미지 캐러셸
2. 다크모드
   <br>

# 5. 서비스 개선사항

1. 회원가입, 로그인 페이지가 웹에 존재하지 않습니다.
2. 현재 예약은 어플을 통해서만 가능합니다.

# 사용기술

- FrontEnd : React.js, React Router, Styled.component
- BackEnd : Python, Django, AWS, MySQL

# 협업 툴

- Git
- Slack
- Notion

# 협업 및 작업 과정

### 매일 매일 스탠딩 미팅 진행과정 및 정보공유 노션 활용하여 진행.
![image](https://user-images.githubusercontent.com/103011139/169689648-cccc96e1-f6c2-467d-aa00-17033a8bd784.png)

# 담당 구현기능

- 상단 메뉴바 : 카테고리별 페이지 이동, 스크롤업 버튼, 다크모드
- 리뷰 페이지 : 리뷰 카드 데이터 갯수만큼 매핑, 무한스크롤, 상세 페이지 모달화, 모달창 내에서 이전, 다음 데이터 불러오기, 리뷰 작성

### 상단 Navbar
![image](https://user-images.githubusercontent.com/103011139/169689968-73239e2e-61c0-4091-b68a-0238e71403d4.png)
- 카테고리별 페이지 이동 버튼
- 스크롤 움직임에 따라 메뉴바 상호작용
- 일정 스크롤 도달시 스크롤 업 버튼 나타나기, 스크롤업 기능
- 버튼으로 다크모드 기능구현

### 리뷰 페이지
![image](https://user-images.githubusercontent.com/103011139/169690023-efdb6143-084a-4dda-a158-27b66a078cca.png)
- 서버에 존재하는 데이터 만큼 리뷰 카드 매핑
- 카드 2개씩 나눠서 무한스크롤
- 카드 클릭시 상세페이지 모달창 구현
- 모달내 좌우 버튼으로 이전,다음 데이터 불러와 정보 띄어주기
- 작성 버튼시 입력창 등장

## 자세한 내용은 블로그 참조
- 블로그 https://sueboi.tistory.com/26


