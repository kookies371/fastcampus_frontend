# fastcampus_frontend

## Part 1. HTML, CSS, JS

### Ch 01. 에어비앤비 클론 코딩

#### 02. HTML, CSS, JS 이론 기초
- HTML: Hyper Text Markup Language
- CSS: Cascading Style Sheed
- JS: JavaScript
  - ECMAScript: 자바스크립트의 명세

#### 03. 헤더 영역 - 이론
- CSS flex: 자신의 컨테이너가 차지하는 공간에 맞추기 위해 크기를 키우거나 줄이는 방법을 설정하는 속성
  - 아이템을 담고 있는 컨테이너와 아이템으로 나뉜다.
  - 컨테이너를 flex box로 만드는 속성은 display이고, display를 flex로 만들어주는 것.
  - flex라는 속성도 있는데, flex는 각 컨테이너 안에 들어가는 아이템들의 속성을 조절하는 값
  - 아이템 컨테이너를 flex로 만드려면 display:flex, 아이템들의 flex를 설정하려면 flex: ~~
  - flex: 1 1 100px라고 하면, grow, shring, basis가 각각 설정되는 것
    - grow: 할당 가능한 공간의 정도
    - shrink: 할당 가능한 공간이 줄어드는 정도, 컨테이너를 넘어갈 때 어떻게 줄어들 것이냐를 설정
    - basis: 아이템의 초기 크기. 상하로 정렬을 할 때는 높이. 좌우로 정렬을 할 때는 너비. flex-basis가 auto가 아니라면, flex-basis가 더 우선값을 갖는다.
  - 컨테이너 속성
    - flex-direction: 정렬 방향
    - justify-content, align-items: 메인축, 교차축 정렬 지정