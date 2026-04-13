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
- **오로라 프로그레스 바**: 상단 그라데이션 흐름 효과
- **다이내믹 인디케이터**: 활성 섹션 텍스트 클리핑 모핑
- **타이포그래피 블러 리빌**: 텍스트가 맑아지는 효과
- **스크롤 스냅**: 씬 겹침 없는 깔끔한 전환
- **글래스 알약 버튼**: "Origin ↑" 상시 노출
- **모바일 하단 네비게이션**: 가로형 알약 스타일
- **프로젝트 모달**: 무지개숲 핵심 가치 노출
- **5개 씬 구조**: Archive 씬 제거로 깔끔한 흐름
- **모바일 스크롤 가속**: dvh 뷰포트와 동적 Lerp 적용
- **앰비언트 배경**: 씬별 미묘한 색상 트랜지션
- **마그네틱 커서**: 카드가 커서로 끌려오는 상호작용
- **조각 밀어내기**: 배경 조각이 커서를 피하는 물리 시뮬레이션
- **페이지 진입 인트로**: "숨고르기" 브랜딩 효과

---

© 2026 레로스 | 대표자: 윤승현
