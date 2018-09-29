# WEB STUDY OT
## 주제선정
### ***React vs Vue.js***
각 프레임워크(라이브러리)의 장단점

React
- 유저 인터페이스를 빌드하기 위한 자바스크립트 라이브러리
- 일단 가장 많이 사용하는 라이브러리
- 자료, 컴포넌트 라이브러리, 커뮤니티가 제일 많고 큼.
- 대부분의 회사가 사용하기 때문에 그 부분에서 얻는 이점이 있음.
- DOM 요소를 생성하는 것은 빠르지만 DOM으로 렌더링하는 과정에서 병목현상이 발생하는 것을 해결

Vue.js
- 상대적으로 배우기 쉽고 한글 가이드 문서가 존재.
- 빠르게 만들 수 있고 작은 웹페이지를 만들 때는 아주 좋은 성능과 생산성.
- 문제가 생겼을 때 해결할 레퍼런스가 부족하고 사용하고 있는 회사는 아직 적음.
- 코어단에 슈가를 첨부하려고 엔지니어링 해둔 부분이 있어서 이 부분이 걸리는 경우가 생길 수도 있음

### ***React로 결정 !***

## React의 특징
- Virtual DOM
	- 필요한 부분만 수정이 일어나서 브라우저 내 발생하는 연산의 양이 줄어듦
- Component-Based
	- UI를 각각 독립적이고 재사용 할 수 있게 만들 수 있음.
	- 소스관리, 유지보수에 도움
- JSX
	- 모던 웹 브라우저에서 사용하기 위해 만들어진 정적인 객체지향 언어.
	- 자바스크립트 내부에 마크업 코드를 작성할 수 있게 해줌.
	- XML만 아니라 변수나 프로퍼티 바인딩 기능도 제공

## npm

sudo로 깔지 말고 nvm으로 설치해야 함.
나는 이미 sudo로 깔려 있어서 [Docs](https://docs.npmjs.com/misc/removing-npm) 참고해서 제거함

npm은 [여기](http://brocess.tistory.com/142) 와 [여기](https://gist.github.com/falsy/8aa42ae311a9adb50e2ca7d8702c9af1) 를 참고해서 재설치 !

```
$ nvm install stable
 ```

nvm 설치 한 상태에서 위 명령어로 npm 설치 후

```
npm -v
```

로 정상적으로 설치되었는지 확인하기

## create-react-app
```
npm install -g create-react-app
```

## 참고

- [PR](https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/) 
- [블로그](https://horajjan.blog.me/221305773211)
- [블로그](https://blog.naver.com/todoskr/221278545202)
- [블로그](https://yazzya.blog.me/221340465261)