# 개찬록[改竄錄] — 순수 HTML/CSS/JavaScript 버전

이 프로젝트는 빌드 도구나 프레임워크 없이 동작하는 정적 사이트입니다.

## 구조

- `index.html` — 페이지 구조
- `styles.css` — 전체 디자인/반응형/모달
- `app.js` — 7정율 데이터, BEFORE/AFTER 전환, 웹툰 모달, 해시 네비게이션
- `assets/characters/` — 캐릭터 이미지
- `assets/webtoons/` — 웹툰 이미지
- `.nojekyll` — GitHub Pages 정적 파일 처리용

## GitHub Pages

저장소 최상단에 `index.html`, `styles.css`, `app.js`, `assets/`가 바로 보이게 업로드하세요.

Settings → Pages → Deploy from a branch → `main` / `(root)` 로 설정하면 됩니다.

별도의 npm, React, Vue, Vite, 서버 설정은 필요 없습니다.
