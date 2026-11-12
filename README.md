# hotblue.kr

HotBlue 스튜디오 랜딩 페이지 (정적 사이트).

- `index.html` — 랜딩 (각 앱 "자세히 보기" → 상세 페이지)
- `giruda.html` · `yutmadang.html` · `coinbeat.html` · `naeil.html` — 앱별 상세 페이지
- 모든 페이지 인라인 CSS, 외부 의존성은 Google Fonts(Outfit·Hanken Grotesk·Noto Sans KR)뿐
- `assets/` — 앱 아이콘, HotBlue 마크/파비콘, OG 이미지, 앱 스크린샷(기루다 App Store, 윷마당 스토어용, 코인 비트 시제품, 내일 웹·모바일)
- `coinbeat/support/` · `coinbeat/privacy/` — 코인 비트 고객 지원·개인정보처리방침 (App Store 지원 URL)
- `assets/og*.png` — 공유 미리보기 (사이트 전체 + 앱별)
- `404.html` · `robots.txt` · `sitemap.xml`
- `CNAME` — 커스텀 도메인 `hotblue.kr`
- `.nojekyll` — GitHub Pages Jekyll 처리 비활성화

## 배포
GitHub Pages (`main` 브랜치, 루트) → 커스텀 도메인 `hotblue.kr`.
