# Create React App(나는 App.js를 원했었따.)

### React 설치 초기
```
node -v
npm -v
```

### 리액트만 설치 *localhost:3000 여야하고, vite 버전이 없는걸루*
```
npx create-react-app 폴더명
cd 폴더명
npm start
```

#### 만약 오류 뜨면
  1. 리액트 18버전 다운그레이드
  ```
  cd 폴더
  npm install react@18 react-dom@18
  npm install
  npm start
  ```

#### 로컬은 들어가는데 오류메시지 뜨면?
src/index.js에서 다음 줄 제거:
```
import reportWebVitals from './reportWebVitals';
reportWebVitals();
```
