# Sorting Algorithms

정렬 알고리즘의 실행 순서를 시각적으로 표현해내는 과제입니다. 상세 내용은 아래 TODO 부분을 참고해주세요.

## Setup

Install dependencies

```sh
$ npm install
```

## Development

```sh
$ npm start
# visit http://localhost:1234
```

- HTML 수정: `index.html`를 수정하세요.
- JS 수정: `/app/index.js`를 수정하세요. 추가적으로 자바스크립트 파일을 만드신다면, `import`와 `export` 문법을 이용하세요.
- CSS 수정: `/assets/styles/index.less`를 수정하세요.
- Image 추가: `/assets/images` 디렉토리를 이용하세요.

> 기타 파일 설정 관련은 [Parcel](https://parceljs.org/getting_started.html) 문서를 참고하세요.

## Keep in mind

1. 각 정렬 알고리즘의 장단점/특징 이해 ([Big-O Cheatsheet](http://bigocheatsheet.com/))
2. 객체 지향 프로그래밍에 대한 활용 시도
3. 순수함수에 대한 이해 및 활용 시도

- 관심사의 분리를 위해 코드 모듈화를 할 경우, 객체 지향적인 시도를 해보세요. (하지만, 너무 섵부른 최적화는 독이 될 수 있습니다. 1차적으로 어느 정도 작업을 진행한 후에 코드 모듈화를 시도하세요.)
- 데이터 처리를 위한 로직들은 순수함수를 최대한 이용해 보세요.

## TODO

- 정렬 알고리즘의 구동 방식을 시각적으로 확인할 수 있도록 표현해야 합니다. (_[Visualgo](https://visualgo.net/en/sorting)의 화면을 참고하세요._)

그리고 아래의 조건이 충족되어야 합니다.

### 1. MVC Pattern (Model-View-Controller)

이번 과제에서 여러분은 MVC 패턴을 학습하고 응용하여 구현해야 합니다.

#### MVC References

- https://developer.mozilla.org/ko/docs/Glossary/MVC
- https://www.smashingmagazine.com/2012/07/journey-through-the-javascript-mvc-jungle/
- https://github.com/tastejs/todomvc/tree/gh-pages/examples/vanillajs/js
- https://gist.github.com/Ken123777/0afa5643834575786eb4f4b2c9bfe1ba

### 2. 상세 구현내용

- 사용자가 "숫자"들을 최소 5개에서 최대 10개까지 선택 혹은 입력할 수 있는 UI가 있어야 합니다.
- 숫자들을 입력한 후, 사용자가 원하는 정렬 방식을 선택할 수 있어야 합니다.
- 정렬 방식은 Bubble과 Insertion 중 **하나를 구현해주세요.**
- 정렬 방식을 선택한 후, 실행할 수 있는 "실행" 버튼이 있어야 합니다.
- 실행시킬 경우, 사용자가 선택한 정렬 로직이 어떤 순서로 요소들을 정렬시키는지 시각적으로 보여주어야 합니다.
- 숫자의 갯수가 충족되지 않았거나, 정렬 방식이 선택되지 않은 상황에서는 "실행"을 시킬 수 없어야 합니다.
- 숫자가 아닌 값은 받을 수 없어야 합니다.
- 중복된 값을 허용해야 합니다.
- 명시된 조건 이외에는 최대한 상식적으로 구현해주시기 바랍니다.
- **창의적이고 멋있는 UI/UX를 보여주세요.**

### 3. Advanced

- Quick과 Merge 중 하나를 구현해보세요.
- 본인의 기존 코드를 최대한 재사용할 수 있도록 노력해보세요.

1. [Bubble Sort](https://en.wikipedia.org/wiki/Bubble_sort)

![Bubble Sort](https://upload.wikimedia.org/wikipedia/commons/0/06/Bubble-sort.gif)

2. [Insertion Sort](https://en.wikipedia.org/wiki/Insertion_sort)

![Insertion Sort](https://upload.wikimedia.org/wikipedia/commons/4/42/Insertion_sort.gif)

3. [Merge Sort](https://en.wikipedia.org/wiki/Merge_sort)

![Merge Sort](https://upload.wikimedia.org/wikipedia/commons/c/cc/Merge-sort-example-300px.gif)

4. [Quick Sort](https://en.wikipedia.org/wiki/Quicksort)

![Quick Sort](https://upload.wikimedia.org/wikipedia/commons/6/6a/Sorting_quicksort_anim.gif)
