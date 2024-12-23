<div align="center">

# 📒 ERROR NOTE

<img src="https://img.shields.io/badge/since-2022.11-grey"></a>
<img src="https://img.shields.io/badge/author-SangYoonLee-yellow"></a>
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSangYoonLee1231%2FERROR-Note&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

</div>

- 개발 중 <strong>마주했던 🚨에러🚨들을 어떻게 해결했는지</strong> 간단히 기록하는 공간입니다.

- 해결 과정이 비교적 길었던 애러는 블로그 포스트로 따로 작성하여 링크를 올렸습니다.

<br/><br/>

## React 기반 FrontEnd 개발

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.04%5D%20DOM%EC%97%90%20%EC%A7%81%EC%A0%91%20%EC%A0%91%EA%B7%BC%ED%95%98%EC%97%AC%20classList%20%EB%A9%94%EC%86%8C%EB%93%9C%EB%A5%BC%20%ED%86%B5%ED%95%B4%20%ED%81%B4%EB%9E%98%EC%8A%A4%EB%A5%BC%20%EC%B6%94%EA%B0%80%ED%95%98%EA%B3%A0%20%EC%A0%9C%EA%B1%B0%ED%96%88%EB%8D%94%EB%8B%88%20%EC%A0%95%EC%83%81%EC%A0%81%EC%9C%BC%EB%A1%9C%20%EB%8F%99%EC%9E%91%ED%95%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.md">DOM에 직접 접근하여 classList 메소드를 통해 클래스를 추가하고 제거했더니 정상적으로 동작하지 않는다.</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.04%5D%20React%EC%97%90%EC%84%9C%20%ED%8A%B9%EC%A0%95%20%EC%9A%94%EC%86%8C%EC%97%90%20%EC%9D%B4%EB%B2%A4%ED%8A%B8%EB%A5%BC%20%EC%97%B0%EA%B2%B0%ED%95%98%EA%B3%A0%2C%20event%20%EA%B0%9D%EC%B2%B4%EB%A5%BC%20%EB%A7%A4%EA%B0%9C%EB%B3%80%EC%88%98%EB%A1%9C%20%EB%B0%9B%EC%95%84%20%ED%99%9C%EC%9A%A9%ED%95%98%EB%8A%94%20%EC%BD%94%EB%93%9C%EB%A5%BC%20%EC%9E%91%EC%84%B1%ED%96%88%EB%8A%94%EB%8D%B0%2C%20event%20is%20deprecated%20%EC%97%90%EB%9F%AC%EA%B0%80%20%EB%B0%9C%EC%83%9D%ED%96%88%EB%8B%A4.md">React에서 특정 요소에 이벤트를 연결하고, event 객체를 매개변수로 받아 활용하는 코드를 작성했는데, <code>event is deprecated</code> 에러가 발생했다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.04%5D%20setState%EB%A5%BC%20%ED%86%B5%ED%95%B4%20%EC%83%81%ED%83%9C%EA%B0%92%EC%9D%84%20%EB%B3%80%EA%B2%BD%ED%95%98%EB%8B%88%20%EC%9B%90%ED%95%98%EB%8A%94%20%EA%B0%92%EC%9D%B4%20%ED%95%98%EB%82%98%EC%94%A9%20%EB%B0%80%EB%A6%B0%20%EC%B1%84%20%EB%B3%80%EA%B2%BD%EB%90%98%EB%8A%94%20%EB%B0%94%EB%9E%8C%EC%97%90%2C%20%EC%83%81%ED%83%9C%EA%B0%92%EC%9D%84%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EB%A1%9C%EC%A7%81%EC%9D%B4%20%EB%82%B4%20%EC%9D%98%EB%8F%84%EB%8C%80%EB%A1%9C%20%EB%8F%99%EC%9E%91%ED%95%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.md">setState를 통해 상태값을 변경하니 원하는 값이 하나씩 밀린 채 변경되는 바람에, 상태값을 활용한 로직이 내 의도대로 동작하지 않는다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.15%5D%20(Router%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%9C)%20React%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EB%A5%BC%20%EC%B4%88%EA%B8%B0%20%EC%84%B8%ED%8C%85%20%EC%99%84%EB%A3%8C%ED%95%98%EA%B3%A0%20%EC%8B%A4%ED%96%89(npm%20start)%ED%95%B4%EB%B3%B4%EC%95%98%EB%8A%94%EB%8D%B0%2C%20%ED%99%94%EB%A9%B4%EC%97%90%20%EC%95%84%EB%AC%B4%EA%B2%83%EB%8F%84%20%EB%82%98%ED%83%80%EB%82%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.md">(Router를 활용한) React 프로젝트를 초기 세팅 완료하고 실행(npm start)해보았는데, 화면에 아무것도 나타나지 않는다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.15%5D%20%EC%95%84%EB%9E%98%EC%99%80%20%EA%B0%99%EC%9D%B4%20%EC%BD%94%EB%93%9C%EB%A5%BC%20%EC%9E%91%EC%84%B1%ED%96%88%EB%8A%94%EB%8D%B0%20%ED%99%94%EB%A9%B4%EC%97%90%20%EC%95%84%EB%AC%B4%EA%B2%83%EB%8F%84%20%EC%B6%9C%EB%A0%A5%EB%90%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.%20(%EC%83%81%EC%9C%84%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EB%8A%94%20%EC%83%9D%EB%9E%B5).md">아래와 같이 코드를 작성했는데 화면에 아무것도 출력되지 않는다. (상위 컴포넌트는 생략)</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.18%5D%20%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%8D%94%EB%A5%BC%20%EB%A6%AC%EC%97%91%ED%8A%B8%EB%A1%9C%20%EA%B5%AC%ED%98%84%ED%95%98%EC%98%80%EB%8A%94%EB%8D%B0%2C%20%EC%B2%98%EC%9D%8C%EC%97%90%20%EC%8B%9C%EA%B0%84%20%EA%B0%84%EA%B2%A9%EC%97%90%20%EB%94%B0%EB%9D%BC%20%ED%8E%98%EC%9D%B4%EC%A7%80%EA%B0%80%20%EC%9D%B4%EB%8F%99%ED%95%A0%20%EB%95%8C%20%ED%99%94%EB%A9%B4%EC%97%90%20%EC%82%AC%EC%A7%84%EC%9D%B4%20%EC%82%AC%EB%9D%BC%EC%A0%B8%EB%B2%84%EB%A0%B8%EB%8B%A4.md">슬라이더를 리엑트로 구현하였는데, 처음에 시간 간격에 따라 페이지가 이동할 때 화면에 사진이 사라져버렸다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.22%5D%20useEffect%EB%A5%BC%20%ED%86%B5%ED%95%B4%20%EB%B0%B1%EC%97%94%EB%93%9C%EC%97%90%EC%84%9C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EB%B0%9B%EC%95%84%20%ED%99%94%EB%A9%B4%EC%97%90%20%EC%B6%9C%EB%A0%A5%ED%95%98%EB%A0%A4%20%ED%96%88%EC%9C%BC%EB%82%98%20(useEffect%EC%9D%98%20%EB%A0%8C%EB%8D%94%EB%A7%81%20%ED%8A%B9%EC%84%B1%EC%9C%BC%EB%A1%9C%20%EC%9D%B8%ED%95%B4)%20%EC%98%A4%EB%A5%98%EA%B0%80%20%EB%B0%9C%EC%83%9D%ED%96%88%EB%8B%A4.md">useEffect를 통해 백엔드에서 데이터를 받아 화면에 출력하려 했으나 (useEffect의 렌더링 특성으로 인해) 오류가 발생했다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.22%5D%20(%EC%9C%84%EC%99%80%20%EB%8F%99%EC%9D%BC%ED%95%9C%20%EB%AC%B8%EC%A0%9C)%20%EB%B0%B1%EC%97%94%EB%93%9C%EC%97%90%EC%84%9C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EB%B0%9B%EC%95%84%20%ED%99%94%EB%A9%B4%EC%97%90%20%EC%B6%9C%EB%A0%A5%ED%95%98%EB%A0%A4%20%ED%96%88%EC%9C%BC%EB%82%98%20%EC%95%84%EB%AC%B4%EA%B2%83%EB%8F%84%20%ED%91%9C%EC%8B%9C%EB%90%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.%20%ED%95%B4%EB%8B%B9%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%8A%94%20undefined%EB%A1%9C%20%EC%B6%9C%EB%A0%A5%EB%90%9C%EB%8B%A4.md">(위와 동일한 문제) 백엔드에서 데이터를 받아 화면에 출력하려 했으나 아무것도 표시되지 않는다. 해당 데이터는 <code>undefined</code>로 출력된다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.23%5D%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%20%ED%95%A8%EC%88%98%20%EC%95%88%EC%97%90%20%EC%95%84%EB%9E%98%EC%B2%98%EB%9F%BC%20useState%EC%9D%98%20Modifier%20%ED%95%A8%EC%88%98%20(set%EC%9C%BC%EB%A1%9C%20%EC%8B%9C%EC%9E%91%ED%95%98%EB%8A%94%20%ED%95%A8%EC%88%98)%EB%A5%BC%20%EC%A3%BC%EC%97%88%EB%8B%A4%EB%8B%88%20%EB%AC%B4%ED%95%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81%EC%9D%B4%20%EB%B0%9C%EC%83%9D.md">컴포넌트 함수 안에 아래처럼 useState의 Modifier 함수 (set으로 시작하는 함수)를 주었다니 무한 렌더링이 발생</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.23%5D%20React%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%9D%98%20%ED%8A%B9%EC%A0%95%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EC%97%90%EC%84%9C%20h3%20%ED%83%9C%EA%B7%B8%EA%B0%80%20%EC%9D%B8%EC%8B%9D%EC%9D%B4%20%EB%90%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.md">React 프로젝트의 특정 컴포넌트에서 <code>\<h3></code> 태그가 인식이 되지 않는다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.11.23%5D%20%EB%B0%B1%EC%97%90%EC%84%9C%20%EB%B0%9B%EC%95%84%EC%98%A8%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EA%B5%AC%EC%A1%B0%20%EB%B6%84%ED%95%B4%20%ED%95%A0%EB%8B%B9%ED%95%A0%20%EB%95%8C%20%EA%B0%92%EC%9D%B4%20%EC%9D%BD%ED%98%80%EC%A7%80%EC%A7%80%20%EC%95%8A%EB%8A%94%20%EB%AC%B8%EC%A0%9C%20-%20Uncaught%20TypeError%20Cannot%20read%20properties%20of%20undefined%20reading%200.md">백에서 받아온 데이터를 구조 분해 할당할 때 값이 읽혀지지 않는 문제 - <code>Uncaught TypeError: Cannot read properties of undefined (reading '0')</code></a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.09%5D%20%ED%86%A0%EC%8A%A4%20%ED%8E%98%EC%9D%B4%EB%A8%BC%EC%B8%A0%20api%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EA%B2%B0%EC%A0%9C%20%EA%B8%B0%EB%8A%A5%20%EA%B5%AC%ED%98%84%20%EC%A4%91%20axios%EB%A5%BC%20%EC%9D%BD%EC%A7%80%20%EB%AA%BB%ED%95%98%EB%8A%94%20%EB%AC%B8%EC%A0%9C.md">토스 페이먼츠 api를 활용한 결제 기능 구현 중 axios를 읽지 못하는 문제가 발생했다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.22%5D%20React%20Router%EB%A5%BC%20%EC%83%88%EB%A1%9C%EA%B3%A0%EC%B9%A8%20%EC%8B%9C%20%EB%B0%9C%EC%83%9D%ED%95%98%EB%8A%94%20cannot%20GET%20URL%20%EC%97%90%EB%9F%AC.md">React-Router를 사용하여 CRA 배포한 페이지에서 새로고침 시 <code>cannot GET /URL</code> 에러가 발생하고 화면엔 아무것도 표시되지 않는다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.22%5D%20React-Router%EB%A5%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20CRA%20%EB%B0%B0%ED%8F%AC%20%EC%8B%9C%20%ED%99%88%ED%8E%98%EC%9D%B4%EC%A7%80%20%EA%B2%BD%EB%A1%9C%EB%A5%BC%20%EC%B0%B8%EC%A1%B0%ED%95%98%EC%A7%80%20%EB%AA%BB%ED%95%9C%EB%8B%A4.md">React-Router를 사용하여 github page에 CRA 배포 시, 홈페이지(도메인) 경로를 참조하지 못하는 문제가 발생한다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.29%5D%20Cannot%20use%20JSX%20unless%20the%20'--jsx'%20flag%20is%20provided.ts(17004).md">CRA + JS에서 CRA + TS로 변환하는 중, <code>Cannot use JSX unless the '--jsx' flag is provided.ts(17004)</code> 에러가 발생했다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.31%5DTypeScript%EB%A1%9C%20React%EB%A5%BC%20%EB%B6%88%EB%9F%AC%EC%98%AC%20%EB%95%8C%20import%20%EA%B5%AC%EB%AC%B8%EC%9D%B4%20JS%EC%99%80%20%EB%8B%AC%EB%9D%BC%EC%A7%84%EB%8B%A4.md">CRA + JS에서 CRA + TS로 변환하는 중, TypeScript로 React를 불러올 때 import 구문에서 에러가 났다.</a>
- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B22.12.31%5D%20CRA%20%2B%20JS%EC%97%90%EC%84%9C%20CRA%20%2B%20TS%EB%A1%9C%20%EB%B3%80%ED%99%98%ED%95%98%EB%8A%94%20%EC%A4%91%2C%20index.tsx%20%ED%8C%8C%EC%9D%BC%EC%9D%98%20App%20%ED%8C%8C%EC%9D%BC%EC%9D%84%20import%20%ED%95%98%EB%8A%94%20%EC%BD%94%EB%93%9C%EC%97%90%EC%84%9C%20%EC%95%8C%20%EC%88%98%20%EC%97%86%EB%8A%94%20%EC%98%A4%EB%A5%98%EA%B0%80%20%EB%B0%9C%EC%83%9D%ED%96%88%EB%8B%A4.md">CRA + JS에서 CRA + TS로 변환하는 중, <code>index.tsx</code> 파일의 App 파일을 import 하는 코드에서 알 수 없는 오류가 발생했다.</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B23.05.16%5D%20PWA%20%EA%B0%9C%EB%B0%9C%20%ED%99%98%EA%B2%BD%20%EC%84%B8%ED%8C%85%20%ED%9B%84%2C%20%ED%8C%8C%EC%9D%BC%20%EA%B5%AC%EC%A1%B0%EB%A5%BC%20%EC%96%B4%EB%8A%90%20%EC%A0%95%EB%8F%84%20%EC%A7%A0%20%ED%9B%84%20%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80%EC%97%90%EC%84%9C%20%EC%9E%98%20%EB%8F%99%EC%9E%91%ED%95%98%EB%8A%94%20%EC%A7%80%20%EC%8B%A4%ED%96%89%ED%95%B4%EB%B3%B4%EB%8B%88%20'ERR_OSSL_EVP_UNSUPPORTED'%20%EC%98%A4%EB%A5%98%EA%B0%80%20%EB%B0%9C%EC%83%9D%ED%96%88%EB%8B%A4.md">PWA 개발 환경 세팅 후, 파일 구조를 어느 정도 짠 후 브라우저에서 잘 동작하는 지 실행해보니 `'ERR_OSSL_EVP_UNSUPPORTED'` 오류가 발생했다.</a> (해결 ❌)

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/React/%5B23.05.17%5D%20reportWebVital%20%EA%B4%80%EB%A0%A8%20%EB%AC%B8%EC%A0%9C.md">`reportWebVital` 관련 문제</a>

<!-- ### 2024년 -->

<!-- - <a href=""></a> -->

<br/><br/>

## Git

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B22.11.15%5D%20(%EA%B9%83%EC%9C%BC%EB%A1%9C%20%EA%B4%80%EB%A6%AC%EB%90%98%EB%8A%94)%20%EB%A1%9C%EC%BB%AC%20%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90%EC%84%9C%20%ED%8C%8C%EC%9D%BC%EB%AA%85%EC%9D%84%20%EC%88%98%EC%A0%95%ED%95%9C%20%ED%9B%84%20%EC%BB%A4%EB%B0%8B%2C%20%ED%91%B8%EC%89%AC%20%EC%8B%9C%20%EC%9B%90%EA%B2%A9%20%EC%A0%80%EC%9E%A5%EC%86%8C%EC%97%90%20%EC%9D%B4%20%EC%88%98%EC%A0%95%20%EC%82%AC%ED%95%AD%EC%9D%B4%20%EB%B0%98%EC%98%81%EB%90%98%EC%A7%80%20%EC%95%8A%EB%8A%94%EB%8B%A4.md">(깃으로 관리되는) 로컬 저장소에서 파일명을 수정한 후 커밋, 푸쉬 시 원격 저장소에 이 수정 사항이 반영되지 않는다.</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B23.01.18%5D%20Git%20merge%20is%20not%20possible%20because%20I%20have%20unmerged%20files.md">커밋 시 로컬 저장소 상태와 원격 저장소 상태가 달라 충돌이 발생했다. (<code>Git merge is not possible because I have unmerged files</code>)</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B23.05.07%5D%20%EB%A1%9C%EC%BB%AC%20%ED%8F%B4%EB%8D%94%EC%99%80%20(%EB%B9%84%EC%96%B4%EC%9E%88%EB%8A%94)%20%EC%9B%90%EA%B2%A9%20%EC%A0%80%EC%9E%A5%EC%86%8C%EB%A5%BC%20%EC%B2%98%EC%9D%8C%EC%9C%BC%EB%A1%9C%20%EC%97%B0%EA%B2%B0%ED%95%98%EA%B3%A0%20%ED%91%B8%EC%89%AC%ED%96%88%EB%8A%94%EB%8D%B0%2C%20%ED%8A%95%EA%B2%BC%EB%8B%A4..md">로컬 폴더와 (비어있는) 원격 저장소를 처음으로 연결하고 푸쉬했는데, 튕겼다.</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B23.05.17%5D.%20%EC%9B%90%EA%B2%A9%20%EC%A0%80%EC%9E%A5%EC%86%8C%EB%A1%9C%20push%ED%95%98%EB%8B%88%20403%20%EC%97%90%EB%9F%AC%EA%B0%80%20%EB%B0%9C%EC%83%9D%ED%96%88%EB%8B%A4.md">Fork를 하지 않고 원격 저장소로 push 했더니 403 에러가 발생했다.</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B23.05.18%5Derror%3A%20pathspec%20did%20not%20match%20any%20file(s)%20known%20to%20git.md">`error: pathspec did not match any file(s) known to git` 에러 (특정 디렉토리 뿐만 아니라 모든 디렉토리에서 해당 에러 발생)</a>

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Git/%5B24.03.26%5Dgit%20push%20permission%20denied%20403%20%EC%97%90%EB%9F%AC%20-%20%EB%A1%9C%EC%BB%AC%20%EA%B9%83%EC%97%90%EC%84%9C%20%EA%B6%8C%ED%95%9C%EC%9D%B4%20%EB%8B%A4%EB%A5%B8%20%EA%B3%84%EC%A0%95%EC%9C%BC%EB%A1%9C%20%EC%84%A4%EC%A0%95%EB%90%98%EC%97%88%EC%9D%8C.md">git push permission denied 403 에러 - 로컬 깃에서 권한이 다른 계정으로 설정되었음</a>

<br/><br/>

## Etc.

- <a href="https://github.com/SangYoonLee1231/ERROR-Note/blob/main/Etc/%5B24.11.20%5D%20npm%20%ED%8C%A8%ED%82%A4%EC%A7%80%20%EC%B6%A9%EB%8F%8C%20%ED%95%B4%EA%B2%B0.md">npm 패키지 충돌 문제 해결</a>

<!-- - <a href=""></a> -->

<br/><br/>

## 💡 공통적인 에러 해결 방법

- 에러의 원인을 도저히 알 수 없을 때 아래의 시도를 통해 해결했던 적이 꽤 있었다. 한 번 참고해보자.

  - <strong>VS Code를 재실행한다.</strong>

  - <strong>클라이언트를 재부팅한다.</strong>

  - <strong>관련 패키지의 버전이 잘 맞는지 확인한다. (패키지를 다운그레이딩 해야할 수도 있다)</strong>

<br/><br/>
