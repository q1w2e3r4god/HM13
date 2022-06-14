# HM13 세번째 홈피 프로젝트 

## 파일구조 및 설명
* hm13_rpt03.html : 나의 시작 홈피 : 시멘틱 태그로 화면 구성과 4개의 iframe으로 구성 button onclick을 통한 값으로 backgroundColor을 수정하여 주/야간모드 구현
* hm13_main.html : 메인 페이지 : 사진에 마우스를 3초간 갖다대면 github로 이동
* hm13_info.html : 나의 소개 페이지 : list를 이용한 정보 공개로 text-align을 이용한 가운데 정렬과 이미지 하이퍼 링크로 구성
* hm13_form.html : 동호회 양식 페이지 :  fieldset을 이용하여 틀을 갖추고 web form을 이용하여 정보를 받는 구성함과 document.getElementById()를 이용한 입력값과 조건을 비교하여 회원가입 유무를 판별하여 alert()를 이용한 결과 출력
  * hm13_forminfo.html : 동호회에 관한 간단한 설명
  * hm13_login.html : onclick을 이용한 로그인 버튼 구현
  * hm13_member.html : 회원가입 성공 시 나타나는 페이지 
  * hm13_lol.html : 로그인 후에 동호회 정보에 관한 페이지로 history.go(-1)을 이용한 로그아웃 기능 구현
* hm13_day.html : 하루 일과 페이지 table을 이용한 일과표와 이미지를 저장한 html을 onclick과 confirm을 이용하여 자유롭게 드나듦
  * hm13_eveytime.html : 시간표 페이지로 이미지를 저장
* hm13_card.html : X-MAS파티 초대장 : 크리스마스 트리와 장식들을 position을 이용하여 테두리 이미지의 적절한 위치로 구성과 animation 과 transform을 이용한 동적 변화 구현과 table을 이용한 파티 초대장
* hm13_best3book.html : 좋아하는 책 페이지 : select를 통해 책들을 구현함과 table을 이용한 이미지 하이퍼 링크로 구성 모든 요소들은 onclick을 이용하여 confirm을 실행시킴과 z - index를 이용한 onovermouse 구현을 css로 구상함
  * bestbook1.html : 좋아하는 책 1의 설명 페이지
  * bestbook2.html : 좋아하는 책 2의 설명 페이지
  * bestbook3.html : 좋아하는 책 3의 설명 페이지
* hm13_gugudan.html : random을 이용한 구구단 게임으로 confirm으로 사용자가 입력한 값에 따라 document.getElementById()를 이용하여 경우에 따른 이미지와 결과문 수정
* hm13_game.html : 삼세판 가위바위보 게임으로 사용자는 button을 통한 값 입력과 컴퓨터는 random을 이용해 각각 3분의 1의 확률에 따른 경우를 설정하여 얻은 값을 비교하여 승자를 정하는 게임
* hm13_image3.html : 좋아하는 프로팀들의 정보가 담긴 페이지로 new Array()를 이용하여 이미지를 저장하여 출력함과 배열을 통한 내용 출력
* hm13_text.html : 간단한 메모를 추가할 수 있는 페이지 button을 이용한 값을 document.getElementById()을 이용하여 구한 뒤 css로 꾸민 메모를 추가시킴
* hm13_clock.html : 간단한 디지털 시계로 new Date()의 메소드를 이용하여 현재 시각을 얻은 뒤 css로 꾸민 내용을 출력함과 setInterval()을 이용하여 1초마다 함수를 반복하여 실행시킴
* hm13_fancy_calc.html : eval()을 이용한 여러 계산 함수를 구현함과 document.getElementById()를 이용한 즉시 결과값을 출력하는 두가지 기능을 주로 구현함
## 사용한 html, css, javascript 기술 
* 시맨틱 태그
* list
* hyperlink
* table
* iframe
* audio
* img src
* display
* text-align
* text-decoration
* datalist
* option
* input
* animation
* keyframes
* transform
* z-index
* scale
* fieldset
* legend
* margin
* padding
* hr
* br
* alert
* confirm
* document.getElementById
* eval
* new Date
* new Array
* random
* onclick
* onsubmit
* onmouseover
* onchange
* history.go
* setInterval
* clearTimeout
* location.href
* window.open
