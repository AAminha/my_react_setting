# CRA없이 Vite로 React 앱 설정

## yarn

### yarn 설치

```
npm install -g yarn
```

### yarn 초기화

```
yarn init
```

위의 명령어로 package.json이 생성됨.

### 의존성 모듈(패키지) 설치

```
yarn    // or yarn install
```

위의 명령어로 yarn.lock이 생성되거나 업데이트 됨.

- yarn.lock : 직접 수정하면 안됨

## Vite

- CRA보다 개발할 때 속도가 더 빠르고 메모리도 적게 잡아먹는다.

### Vite 설정

```
yarn create vite
// 이후에 여러가지 골라주고 골라주고...
```

위의 명령어를 진행하면 yarn init이 필요없음.

### Vite 설정 (자동화..?)

```
yarn create vite <프로젝트명> --template react-ts
```

## 실행

yarn으로 진행했으므로 `yarn dev`

## ESLint

ESLint : 문법 검사 지원, 런타임 이전에 오류를 찾아주는 도구. (보통 airbnb나 google의 스타일 가이드 많이 이용)

### ESLint 설치

```
yarn add eslint
```

### ESLint 세팅

```
npx eslint --init
```

[참고](https://velog.io/@kmh060020/React-vite-eslintairbnb-prettier-typescript-%EC%84%A4%EC%A0%95)
