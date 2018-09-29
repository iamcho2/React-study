# JSX
- JSX는 JavaScript 와 XML을 합쳐서 만든 JavaScript의 확장 문법이다.
- JavaScript 안에 마크업 코드를 작성할 수 있고, property의 바인딩도 가능하다.
- JSX는 컴파일 되면서 최적화 되므로 빠르다.
	- 컴파일 되면서 js로 바뀜
- 확장자는 `.js` 를 사용하고 있다.

## 프로젝트 생성하기
React 홈페이지에서는 쉽게 리액트 프로젝트를 만들기 위해 `create react app`을 사용하라고 권장!

```
$ create-react-app my-app
```
my-app 이라는 폴더에 react 프로젝트가 설치된다.

```
$ cd my-app
$ npm start
```
입력하면 localhost:3000으로 서버가 실행된다.

## 파일들 살펴보기
<img src="./img/2/list.jpeg" align=left>

- App.js : 메인 컴포넌트 파일. jsx가 들어있음. 

```
import React, { Component } from 'react';
import logo from './logo.svg';
import './App.css';

class App extends Component {
  render() {
    return (
      <div className="App">
        <header className="App-header">
          <img src={logo} className="App-logo" alt="logo" />
          <h1 className="App-title">Welcome to React</h1>
        </header>
        <p className="App-intro">
          To get started, edit <code>src/App.js</code> and save to reload.
        </p>
      </div>
    );
  }
}

export default App;
```