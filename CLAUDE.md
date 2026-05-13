# 프로젝트: 오지은 개인 소개 웹페이지

## 개요
오지은(Samsung, je413.oh@samsung.com)의 개인 프로필 페이지입니다.
Apple 디자인 감성 기반의 정적 웹페이지로, 외부 라이브러리 없이 HTML · CSS · JavaScript만으로 구성되어 있습니다.

## 파일 구조
```
01_TEST/
├── index.html      # 메인 페이지 (HTML + CSS + JS 모두 포함)
├── mycareer.md     # 커리어 원본 데이터 (소스 데이터)
└── CLAUDE.md       # 프로젝트 문서 (현재 파일)
```

## 인물 정보 (mycareer.md 기반)
| 항목 | 내용 |
|------|------|
| 이름 | 오지은 |
| 개발 경력 | 5년 |
| 데이터레이크 운영 | 10년 |
| 기획 경력 | 5년 |
| 출신 학교 | 경희대학교 |

## 페이지 구성 (섹션)
1. **히어로** — 아바타 이니셜 + 이름 + 한 줄 소개 + 태그
2. **Career Summary** — 경력 3종(개발/데이터/기획)을 숫자 강조 카드로 표시
3. **Career Timeline** — 학력 → 개발 → 데이터 → 기획 흐름 시각화
4. **Education + Expertise** — 학력 정보 + 전문성 스킬 바 차트

## 주요 인터랙션
- 스킬 바: Intersection Observer로 화면 진입 시 애니메이션
- 경력 카드: 마우스 이동에 따른 3D 틸트 효과
- 다크모드 자동 대응 (`prefers-color-scheme: dark`)

## 기술 스택
- HTML5
- CSS3 (CSS Variables, Flexbox, Grid, Intersection Observer API)
- Vanilla JavaScript (외부 의존성 없음)
- Google Fonts: Noto Sans KR (fallback용)

## 디자인 원칙
- Apple 감성: SF Pro 폰트 스택, 음수 letter-spacing, 소프트 섀도우
- 컬러: 라이트 `#f5f5f7` 배경 / 다크 `#000` 배경, 액센트 Apple Blue
- 배경: 블루·퍼플·틸 오로라 블러 그라데이션

## 개발 규칙
- 단일 파일(`index.html`) 유지 — CSS와 JS를 분리하지 않음
- 외부 프레임워크/라이브러리 사용 금지
- 브라우저에서 파일을 직접 열어 동작 확인 (서버 불필요)
- 인물 정보 변경 시 `mycareer.md`를 먼저 수정 후 `index.html`에 반영

## 실행 방법
`index.html` 파일을 브라우저에서 직접 열면 됩니다.
