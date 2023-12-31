# Recoil & React-hook-form 제대로 학습하기

## ⁉️ 왜 Recoil (ToDoList page에서 적용)로 전역관리를 하는가?
### 👨‍💻 복잡한 상태관리를 간편하게 하기 위해
### 👨‍💻 손쉽게 상태관리를 하기 위해
### 👨‍💻 Recoil도 redux와 마찬가지로 단방향성을 가진 상태관리 라이브러리 입니다
### 👨‍💻 이유없는 사용은 결국 얘측 불가능한 상태관리가 되버리기 때문에 <br/><br/>항상 예측가능하게 구성해야한다.<br/><br/>

## ⁉️ 왜 React-hook-form (Auth page에서 적용)으로 유효성관리를 하는가?
### 👨‍💻 비제어 컴포넌트 방식으로 구현되어있기에 렌더링 이슈를 해결
### 👨‍💻 props drilling 없이 사용할 수 있다
### 👨‍💻 데이터는 계속 동기화되며 분산되지 않아 데이터를 한 곳에서 관리 가능

## 프로젝트 시작하기
### `npm install or npm i`
### `npm start`

### Autor : Kimdowon

## 라이브러리

### ✅ Recoil
### ✅ Styled-Components
### ✅ React-router-dom
### ✅ React-hook-form
--------------------------------------
### ✅ atom (동기)
### ✅ selector (비동기)
--------------------------------------
### ✅ register (form의 유효성 확인)
### ✅ handleSubmit (form의 제출)
### ✅ formState (form의 전체 상태양식 확인 ex. error)
### ✅ watch (form의 실시간 입력값 확인)
### ✅ defaultValues (form에서 정한 value의 가장 초기값)
### ✅ setError (form에서 errors이외의 custom error생성을 위해)
### ✅ required (form에 추가된 입력값의 요구사항 메시지)
