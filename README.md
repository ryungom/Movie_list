# 🎬Movie_list - 영화목록 사이트를 Sass 이용하여 클론코딩
![전체레이아웃](https://github.com/ryungom/Movie_list/blob/main/images/allview_01.png)
- [완성페이지 보러가기](https://ryungom.github.io/Movie_list/index.html)

## ⚙️issue list
- 220508
  - Sass를 작업하여 완성본 작업.
  - background-image에 live server 실행 시 이미지가 보이지 않는 오류가 있었음. 자세히 뜯어고쳐보니 해당 이미지가 scss 폴더의 image 폴더로 잡고있었다. 그래서 절대경로를 이용하여 수정 보완.
  - 영화 이미지의 상위 컨테이너 요소에 padding-top 을 주어서 웹브라우저 로딩시에도 이미지가 로딩이 되지 못한 상태에서 마크업 구조가 깨져보이지 않도록 조정. 다만 이 부분을 이미지에 그냥 고정값을 넣는게 좋을지 내가 한 방식대로 상위요소에 padding-top을 주는게 좋을지는 모르겠음. 연구가 필요.
