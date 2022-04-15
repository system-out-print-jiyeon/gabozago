
React Toy Project

🔗 Link : https://system-out-print-jiyeon.github.io/gabozago/


# 리액트로 구현한 퇴근시간 계산기

( ✅ 모바일 모드를 권장합니다)


---

### 💡 프로젝트 수행 계기

리액트의 다양한 기능들과 라이브러리들을 사용해보기 위해 타입스크립트와 리액트를 사용해 간단한 프로젝트를 만들어보았다.

### 💡 프로젝트 설명

시간을 입력하면 현재시간과 비교하여 남은 시간을 출력한다.

### 💡 Project setup command

```

npm install typescript @types/node @types/react @types/react-dom @types/jest

npm install --save @types/react-redux

npm install moment

npm install react-bootstrap bootstrap

npm install react-router-dom@5.2.0

npm install node-sass

npm install gh-pages --save-dev

npm install --save-dev @types/redux-actions
```

### 💡 구현하고자 한 것

✔️ 시간 입력 받아 Redux로 state 관리

✔️ moment.js 와 setInterval 으로 시간 계산 구현

✔️ Toast 창 띄우기

✔️ Link copy

✔️ Router exact, :parameter 로 올바른 URL과 잘못 된 URL 구분

### 💡 구성

✔️ Start : 시간을 input으로 입력 받는 페이지

✔️ Home : 계산 된 시간(Timer 컴포넌트)을 출력하는 페이지

✔️ TimeToGo : 입력한 시간이 다 되면 보여지는 페이지

✔️ About : 프로젝트 기능을 기술한 페이지

✔️ Profile : 프로필 소개 페이지

(About과 Profile페이지는 Navbar를 구성하기 위해 만든 페이지이다)
