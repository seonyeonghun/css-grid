# 주제 : css grid system
## 상세 : 1440px grid
## 참고 : <https://1440px.com/>

## 소개
>CSS 그리드 레이아웃(Grid Layout)은 페이지를 여러 주요 영역으로 나누거나, 크기와 위치 및 문서 계층 구조의 관점에서 HTML 기본 요소로 작성된 콘트롤 간의 관계를 정의하는 데 아주 탁월합니다.
>테이블과 마찬가지로 그리드 레이아웃은 세로 열과 가로 행을 기준으로 요소를 정렬할 수 있습니다. 하지만, 테이블과 달리 CSS 그리드는 다양한 레이아웃을 훨씬 더 쉽게 구현할 수 있습니다. 예를 들어, 그리드 컨테이너 속 자식 요소를, 마치 CSS로 일일이 위치를 지정해 준 것처럼, 실제로 겹치게 층을 지면서 자리를 잡도록 각 요소의 위치를 지정해 줄 수도 있습니다.

## 기본예제
아래 예제는 3개의 세로 열 트랙으로 이루어졌으며, 저절로 채워지며 생성되는 가로 행 트랙은 높이가 최소 100픽셀 이상, 콘텐츠 최대치까지 자동으로 늘어나는 구조의 그리드를 보여줍니다. 각 아이템은 그리드 라인을 기준으로 배치되었습니다.
```html
<div class="wrapper">
  <div class="one">One</div>
  <div class="two">Two</div>
  <div class="three">Three</div>
  <div class="four">Four</div>
  <div class="five">Five</div>
  <div class="six">Six</div>
</div>
```