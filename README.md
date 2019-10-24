# Nuxt + composition-api 예제 프로젝트

> `Nuxt` 에서 `composition-api` 를 간단하게 사용하는 방법에 관하여 예제코드를 작성합니다.

## 프로젝트 생성

``` bash
$ npm init nuxt-app .
# .은 프로젝트 위치입니다.
```

`nuxt-app` 으로 프로젝트 생성시 설정은 아래와 같이 진행했습니다.

- Choose the package manager: npm
- Choose UI framework: Tailwind CSS
- Choose custom server framework: Express
- Choose Nuxt.js modules: Axios
- Choose linting tools: ESLint, Prettier, ~Line staged files~
- Choose test framework: Jest
- Choose rendering mode: Universal (SSR)
- Choose development tools: jsconfig.json


## 프로젝트 운영

``` bash
# npm 모듈 설치
$ npm run install

# hot reload가 적용된 localhost 서버 실행하기 (포트는 3000)
$ npm run dev

# 프로젝트 빌드 및 서버 시작하기
$ npm run build
$ npm run start

# 정적 파일로 생성하기
$ npm run generate
```
