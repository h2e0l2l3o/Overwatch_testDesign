# 오버워치 캐릭터 선택 페이지 디자인

## HTML, CSS 사용.

* display = flex를 이용해서 html에서 추가한 각각의 요소들을 수평으로 나열함.
* 각각의 image 요소들에 준비된 이미지 url을 이용해서 오버워치 캐릭터들의 이미지를 넣어줌.
* image의 상위 요소인 hero에 마우스를 가져다 놓으면(hover) 배경 색과 모양(사이즈)가 변화할 수 있도록 함.
    + transform: skewX(-14deg) scale(1.3);
    + background color는 #555에서 #ff9c00으로 바뀜
* hero의 전환효과를 더욱 자연스럽게 하기 위해서 transition을 이용함.
    + 색변화의 지속시간은 0.6s
    + transform의 지속시간은 0.1s 로 설정.
* margin, padding, width, height를 이용해서 세밀하게 로고, container, heros, body 영역의 사이즈를 설정함.

* 이번 클론 코딩으로 css를 다룰 때 상당히 사소한 부분까지 신중하게 고려하고 속성값을 지정해줘야함을 깨달았다.
* 예를 들어, hero에서 내가 skewX(-15deg)를 했다면, image 또한 skewX(-15deg)만큼 기울어져있기 때문에 다시 반대로 skewX(15deg)를 적용해줌으로서 이미지자체는 기울어지지 않게 해야한다.

* 출처: Fastcampus 프론트엔드 온라인 강의 (박영웅 강사님)
* https://github.com/ParkYoungWoong
  
