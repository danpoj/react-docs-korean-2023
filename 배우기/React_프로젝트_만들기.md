## React 프로젝트 만들기

✅ 먼저 [node js](https://nodejs.org/en/)를 설치해야합니다. 아래의 명령어를 통해 node가 살치되어있는지 확인해보세요! (설치되어있다면 v18.8.0과 같이 버전이 출력됩니다.)

```
node -v
npm -v
```

가장 간단한 방법인 [Create React App](https://create-react-app.dev/docs/getting-started)을 통해 React 프로젝트를 만들어봅시다.

```
npx create-react-app 프로젝트이름
cd 프로젝트이름
npm start
code .
```

`npm start`를 했다면 http://localhost:3000 에 개발 서버가 열리게 됩니다.

<img width="400" alt="스크린샷 2023-01-08 오후 11 35 44" src="https://user-images.githubusercontent.com/88086373/211202203-ae54780b-d742-497d-a8af-a927a2902c57.png">

마지막으로 필요한 파일들만 남겨두고 나머지는 삭제하도록 하겠습니다. `/src` 폴더를 아래와 같이 만들어주세요.

<img width="176" alt="스크린샷 2023-01-08 오후 11 43 40" src="https://user-images.githubusercontent.com/88086373/211202560-7c37c5d4-76b8-46c5-91d4-e899feeec2e8.png">

### index.js

```js
import React from 'react'
import ReactDOM from 'react-dom/client'
import App from './App'

const root = ReactDOM.createRoot(document.getElementById('root'))
root.render(<App />)
```

### App.js

```js
function App() {
  return <h1>hello, react!</h1>
}

export default App
```

<img width="940" alt="스크린샷 2023-01-08 오후 11 50 04" src="https://user-images.githubusercontent.com/88086373/211202888-b2ac5446-9835-4870-9941-de281fcd0c91.png">

React를 배우기 위한 프로젝트 설정을 마쳤습니다.
