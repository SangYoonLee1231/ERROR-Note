<div align="center">

# 🚨📒 ERROR NOTE

<img src="https://img.shields.io/badge/since-2022.11-grey"></a>
<img src="https://img.shields.io/badge/author-SangYoonLee-yellow"></a>
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSangYoonLee1231%2FERROR-Note&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

- 개발 중 <strong>마주했던 에러들을 어떻게 해결했는지</strong> 간단히 기록하는 공간입니다.

- 해결 과정이 비교적 길었던 애러는 블로그 포스트로 따로 작성하여 링크를 올렸습니다.

<br/><br/>

## React

### 2022년 11~12월

- <a href="">DOM에 직접 접근하여 classList 메소드를 통해 클래스를 추가하고 제거했더니 정상적으로 동작하지 않는다.</a>
- <a href="">React에서 특정 요소에 이벤트를 연결하고, event 객체를 매개변수로 받아 활용하는 코드를 작성했는데, <code>event is deprecated</code> 에러가 발생했다.</a>
- <a href="">setState를 통해 상태값을 변경하니 원하는 값이 하나씩 밀린 채 변경되는 바람에, 상태값을 활용한 로직이 내 의도대로 동작하지 않는다.</a>
- <a href="">(Router를 활용한) React 프로젝트를 초기 세팅 완료하고 실행(npm start)해보았는데, 화면에 아무것도 나타나지 않는다.</a>
- <a href="">아래와 같이 코드를 작성했는데 화면에 아무것도 출력되지 않는다. (상위 컴포넌트는 생략)</a>
- <a href="">슬라이더를 리엑트로 구현하였는데, 처음에 시간 간격에 따라 페이지가 이동할 때 화면에 사진이 사라져버렸다.</a>
- <a href="">useEffect를 통해 백엔드에서 데이터를 받아 화면에 출력하려 했으나 (useEffect의 렌더링 특성으로 인해) 오류가 발생했다.</a>
- <a href="">(위와 동일한 문제) 백엔드에서 데이터를 받아 화면에 출력하려 했으나 아무것도 표시되지 않는다. 해당 데이터는 <code>undefined</code>로 출력된다.</a>
- <a href="">컴포넌트 함수 안에 아래처럼 useState의 Modifier 함수 (set으로 시작하는 함수)를 주었다니 무한 렌더링이 발생</a>
- <a href="">React 프로젝트의 특정 컴포넌트에서 <code>\<h3></code> 태그가 인식이 되지 않는다.</a>
- <a href="">백에서 받아온 데이터를 구조 분해 할당할 때 값이 읽혀지지 않는 문제 - <code>Uncaught TypeError: Cannot read properties of undefined (reading '0')</code></a>
- <a href="">토스 페이먼츠 api를 활용한 결제 기능 구현 중 axios를 읽지 못하는 문제</a>
- <a href="">React Router를 새로고침 시 발생하는 <code>cannot GET /URL</code> 에러</a>
<!-- - <a href=""></a> -->

<br/><br/>

## Git

- <a href="">(깃으로 관리되는) 로컬 저장소에서 파일명을 수정한 후 커밋, 푸쉬 시 원격 저장소에 이 수정 사항이 반영되지 않는다.</a>
<!-- - <a href=""></a> -->

<br/><br/>

## 💡 공통적인 에러 해결 방법

- 도저히 알 수 없는 에러가 발생했을 때 아래의 시도를 통해 해결한 적이 여럿 있었다. 참고해보자.

  - <strong>VS Code를 재실행한다.</strong>

  - <strong>클라이언트를 재부팅한다.</strong>

  - <strong>관련 패키지의 버전이 잘 맞는지 확인한다. (패키지를 다운그레이딩 해야할 수도 있다)</strong>

<br/><br/>
