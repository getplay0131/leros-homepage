# The Leros Canvas

leros.kr 공식 홈페이지 - Google Play Console 심사 및 브랜딩을 위한 혁신적 웹사이트

## 콘셉트

**The Leros Canvas**는 '극강의 단순함'과 '공간 확장' 경험을 제공하는 예술적 홈페이지입니다.

- **Zero-Layout**: 전통적인 Header/Footer/Section 경계 제거
- **Z-Axis Scroll**: 스크롤을 통한 공간 확장 경험
- **Underground Menu**: 하단 호버 시에만 법인 정보 노출

## 구조

```
leros-homepage/
├── index.html      # The Leros Canvas 메인
├── privacy.html    # 개인정보처리방침 (준비중)
├── guide.html      # 제작 가이드 문서
├── CNAME          # GitHub Pages 도메인 설정
└── assets/        # 이미지 자산 폴더
```

## 배포

1. GitHub Pages에 배포
2. 가비아 DNS 설정 (leros.kr → GitHub Pages)

## 기술 스택

- HTML5
- CSS3 (Variables, GPU 가속)
- Vanilla JavaScript (Scroll Observer)
- Fontshare Satoshi 폰트

## 특징

- 첫 화면: "Leros" 텍스트만 (10단어 이하)
- 스크롤에 따른 요소 변형 (scale, opacity)
- GPU 가속으로 60fps 유지
- 반응형 디자인 (모바일/데스크탑)
- **인디케이터 툴팁**: 데스크탑에서 씬 명칭 표시
- **모바일 하단 네비게이션**: 가로형 알약 스타일
- **상단 이동 버튼**: 레로스 스타일의 "Origin" 버튼
- **프로젝트 모달**: 무지개숲 핵심 가치 노출
- **5개 씬 구조**: Archive 씬 제거로 깔끔한 흐름

---

© 2026 레로스 | 대표자: 윤승현
