# 한국AI기술협회 웹사이트

한국AI기술협회 홈페이지 프로토타입 소스입니다.

## 공개 사이트

https://jinny-debug.github.io/koreaaitech-website/

## 실행 구조

이 프로젝트는 Cloudflare Worker 형식의 `worker/index.js`를 사용하며, GitHub Pages에서는 `index.html`과 `404.html`이 Worker 응답을 브라우저에서 렌더링합니다.

## 빌드 및 검증

```sh
bash scripts/build.sh
node scripts/validate-artifact.mjs
```

GitHub Pages 배포는 `.github/workflows/deploy-pages.yml`에서 자동으로 실행됩니다.
