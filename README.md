# dac-data-api

MES API Platform 2027 — Data Workflow · Playground.

- 스펙: [docs/SPEC.md](docs/SPEC.md)
- 화면 원본 목업(디자인 도구 소스): `design` 브랜치의 `docs/mockup/`

## 목업 사이트 실행

빌드 없이 정적 파일(`web/`)만 서빙하면 됩니다.

```
npm start                              # http://localhost:3000  (npx serve 사용)
# 또는
python3 -m http.server 3000 --directory web
```

- `web/index.html` : 화면 목록
- `web/assets/styles.css` : 모든 화면의 스타일 (자동 추출)
- `web/assets/app.js`, `web/assets/deploy.js` : 배포 화면 동작(API/MCP 선택, 동기/Job, 미리보기 탭)

서버나 DB는 연결되어 있지 않고 화면 확인용입니다. 글꼴(Geist, IBM Plex Sans KR)은 Google Fonts에서 받으므로 인터넷이 연결되어 있어야 합니다.
