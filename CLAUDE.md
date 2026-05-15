# CodeRabbit 홈페이지 프로젝트

## 사업자 정보
- **상호**: 코드래빗
- **사업자등록번호**: 740-69-00653
- **대표자**: 이현준
- **공식 이메일**: coderabbitapp@gmail.com

## 프로젝트 개요
GitHub Pages로 운영되는 모바일 앱 소개 홈페이지 (`rbjoon.github.io`)

## 앱 목록
- **노리맵 (Norimap)**: 전국 놀이터 지도 탐색 앱 (iOS / Android)
- **얌플래너 (YumPlanner)**: 이유식 플래너 앱 (iOS / Android)
- **로또무당 (Lotto Shaman)**: AI 로또 번호 추천 앱 (Android)

## 디자인 시스템
- 테마: 프리미엄 다크 + 글래스모피즘
- 배경: 애니메이션 컬러 오브 (CSS only)
- 폰트: Noto Sans KR (Google Fonts)
- 카드: `backdrop-filter: blur(28px)` 글래스 효과
- 노리맵 컬러: `#22c55e` (그린)
- 얌플래너 컬러: `#f97316` (오렌지)
- 로또무당 컬러: `#8b5cf6` (퍼플)

## 파일 구조
```
index.html                  # 메인 홈페이지
image/
  norimap_app.png
  yumplanner_app.png
  lotto_app.png
  quicktext_app.png
norimap/
  privacy.html
  terms_use.html
yumplanner/
  privacy.html
  terms_use.html
  privacy-consent.html
lottomudang/
  privacy_policy.html
  terms_of_service.html
quicktext/
  privacy-consent.html
  terms_use.html
```

## 정책 페이지 URL 규칙
- `https://rbjoon.github.io/{앱명}/privacy.html` — 개인정보처리방침
- `https://rbjoon.github.io/{앱명}/terms_use.html` — 이용약관
