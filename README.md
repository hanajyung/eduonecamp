# EduOne Camp — 2027 하노이 캠프 웹사이트

에듀원캠프(EduOne Camp) 공식 웹사이트. 왓츠에듀(What's Edu)가 기획·운영하며,
Fairmont International School Vietnam(정식 MOU 파트너 교육사) · 에듀플렉스 · ASEB 그룹 · 좋은세상여행사와 함께합니다.

- 라이브 사이트: https://eduonecamp.com
- 순수 HTML / CSS / JS 정적 사이트 (빌드 도구 없음)
- 배포: GitHub Pages (`main` 브랜치, 루트) + 가비아 도메인 커스텀 도메인 연결 (`CNAME` 파일)

## 로컬에서 미리보기

빌드 과정이 없으므로 정적 파일 서버로 열면 됩니다. 예:

```
npx serve .
```

또는 아무 정적 파일 서버로 `index.html`을 열어보세요.

## 구조

```
index.html        본문 (전체 한 페이지 구성)
css/style.css      스타일
js/main.js         모바일 메뉴 · FAQ 아코디언 스크립트
assets/img/        사진 · 로고 · QR 코드
assets/icons/      파비콘
CNAME              GitHub Pages 커스텀 도메인 설정 (eduonecamp.com)
robots.txt, sitemap.xml   SEO
```

## 콘텐츠 갱신

2027 하노이 캠프 12페이지 공식 안내책자를 기준(source of truth)으로 작성되었습니다.
캠프 시즌이 바뀌면 `index.html`의 텍스트와 `assets/img`의 사진을 새 안내책자 기준으로 교체하세요.
