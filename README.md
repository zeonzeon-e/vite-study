# 포트폴리오 사이트 만들기 프로젝트

## vite을 이용하여 포트폴리오 사이트를 만드는 프로젝트의 튜토리얼을 따라했습니다.

### 출처: https://webstoryboy.co.kr/1924 [WEBSTORYBOY:티스토리]

## 프로젝트 실행

- vite를 설치합니다. `npm create vite@latest`
- gsap를 설치합니다. `npm install gsap`
- lenis를 설치합니다. `npm install @studio-freight/lenis`
- vite를 설치 후 환경 설정을 합니다. `vite.config.js`파일을 만들고 다음과 같이 작성합니다.

```javascript
export default {
  root: "src",
  build: {
    outDir: "../public",
  },
};
```
