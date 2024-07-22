---
#디자인 -> 개발 핸드오프 과제
---

### html 구조

1. 먼저 div로 ul과 li안의 요소들을 묶는 container를 만들었습니다.

2. 그리고 tab키로 아이탬들을 인식 할 수 있게 li들에게 tabindex="1"을 주었습니다.

3. li안에 이미지들을 background-image로 넣을까? img태그를 사용할까? 고민을 하다가 나중에  반응형으로 만든다면 img태그가 용이 할 것 같아 img태그를 사용 했습니다.

4. li안에 span태그를 넣은 이유 : 글에 스타일을 주는 것 뿐이라면 span을 사용하는것이 좋다고 생각 했습니다. 

---

### css 

1. 상위 부모인 .item-container에 flex를 할 때 아이템들을 colum처럼 되기 위해 width: 312px을 주었습니다.

2. .items들 내부의 img와 sapn이 가로로 정력 될 수 있게 flex를 주었고, 각 아이템들이 가운데 정렬을 하기 위헤 align-items:center를 주었습니다.
여기서 궁금한 점은 이미지 크기가 64px X 64px 인데 ,items에 overflow:hidden을 주어야 할까 말까 입니다. 

3. html에서 .items(li)들에게 tabindex="1"을 주었기 때문에 :focuse를 주어 기존 outline 스타일을 없애고 눈에 띄게 스타일을 주었습니다. 
