# 2장: JSX

#### 2.1 코드 이해하기

* import로 모듈을 불러와서 사용하는것은 브라우저에 없던 기능 -> Node.js가 지원하는 기능
* 이러한 기능을 브라우저에서도 사용하기 위해 bundler 사용

#### 2.2 JSX란?

* JSX코드는 브라우저에서 실행되기 전 코드가 번들링되는 과정에서 바벨을 사용하여 일반 자바스크립트 형태의 코드로 변환됨
* 리액트 컴포넌트에서는 함수에서 undefined만 반환하여 렌더링 하는 상황을 만들면 안됨.
* JSX 내부에서 undefined를 렌더링 하는 것은 괜찮음

&#x20;                &#x20;
