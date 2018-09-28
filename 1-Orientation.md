# WEB STUDY OT
## 주제선정
### ***React vs Vue.js***
각 프레임워크(라이브러리)의 장단점

React
- 일단 가장 많이 사용하는 라이브러리
- 자료, 컴포넌트 라이브러리, 커뮤니티가 제일 많고 큼.
- 대부분의 회사가 사용하기 때문에 그 부분에서 얻는 이점이 있음.

Vue.js
- 상대적으로 배우기 쉽고 한글 가이드 문서가 존재.
- 빠르게 만들 수 있고 작은 웹페이지를 만들 때는 아주 좋은 성능과 생산성.
- 문제가 생겼을 때 해결할 레퍼런스가 부족하고 사용하고 있는 회사는 아직 적음.
- 코어단에 슈가를 첨부하려고 엔지니어링 해둔 부분이 있어서 이 부분이 걸리는 경우가 생길 수도 있음

### ***React로 결정 !***

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