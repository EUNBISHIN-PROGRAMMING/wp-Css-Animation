1. 웹 응용프로그래밍 5주차 내용 설명

웹 응용프로그래밍 5주차에서는 기존의 과제와는 다르게 css파일을 html내부에 작성하지 않고 
외부에서 작성하여 불러오는 방식을 사용하였다.

아직 Javascript를 배우지는 않았지만 금주에 잠깐 사이드 메뉴를 설정할 때 배워 적용을 해보았다.
맨 위 상단의 bar를 누르면 사이드메뉴가 나온다. 다시 한 번 bar를 누르면 사이드메뉴가 사라진다.
사이드 메뉴를 설정하는 css파일은 gallery.css이다.

홈페이지의 화면을 키면 바로 나오는 사진첩은 grid를 이용하여 만들었다. 원래 이 박스는 3x5의 grid이다.
하지만
img.big {
    grid-column: span 2;
    grid-row: span 2;
} 
이 코드를 css파일에서 설정하여 주요 사진들이 2칸을 차지하게 만들었다.
html파일에서 다음의 코드를 작성하면 다른 그림들과는 다르게 커져 있다.
--> <img src="./images2/moon5.jpg" class="big">

사진첩의 사진들은 기본적으로 반투명하게 보이도록 설정하였고, 마우스를 올리면 불투명하게 보이고 살짝 크기가 커지도록 설정하였다. 그리고 이 때 다른 사진들보다 위에 떠 있도록 만들었다.

그 이외의 코드들은 https://github.com/EUNBISHIN-PROGRAMMING/wp---box-model-and-layout에 올렸던 html의 코드들과 동일하다.

2. 비고 및 고찰
css를 배워가면서 좀 더 활동적인 웹페이지를 만들어가는 것이 새롭고 즐겁다.
하지만 여전히 부족한 개념이 많다는 것을 다시 한 번 더 느꼈다. 
지난 강의들 중 잘 이해하지 못한 부분들은 다시 한 번 들어 완벽하게 이해하고 넘어가는 시간을 가져야 할 것 같다. 좀 더 구글로 찾아보면서 하나씩 하나씩 웹페이지에 추가를 해보는 시간을 가져 git에 넣는 습관을 들이는 것이 중요하다는 생각도 하게 되었다.