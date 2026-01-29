# HYUNDAI MOBIS Parameter DB System

서스펜션 파라미터 관리 시스템 프로토타입

## 📁 페이지 구조 (IA)

```
├── index.html              # 버전뷰 목록 (메인)
│
├── 데이터 생성
│   ├── create-step1.html   # Step1: 카드추가 세트생성
│   └── create-step2.html   # Step2: 도면연결
│
├── 데이터 조회
│   ├── view-detail.html    # 상세보기
│   └── edit.html           # 수정 모드
│
├── KPI 해석
│   └── kpi-analysis.html   # 해석값 도출
│
└── 시뮬레이션
    ├── simulation-setup.html   # 케이스 설정
    └── simulation-result.html  # 시뮬레이션 결과
```

## 🔗 페이지 흐름

1. **index.html** (목록) → 카드 클릭 → **view-detail.html** (상세보기)
2. **view-detail.html** → 수정 버튼 → **edit.html** (수정)
3. **edit.html** → 저장 → **view-detail.html**

## 🚀 GitHub Pages 배포

이미 배포 완료: `https://[username].github.io/[repo-name]`

## 📦 파일 목록

| 파일명 | 설명 |
|--------|------|
| index.html | 버전뷰 목록 (메인) |
| create-step1.html | 카드추가 세트생성 |
| create-step2.html | 도면연결 |
| view-detail.html | 상세보기 |
| edit.html | 수정 모드 |
| kpi-analysis.html | KPI 해석 |
| simulation-setup.html | 케이스 설정 |
| simulation-result.html | 시뮬레이션 결과 |
| Suspension.png | 서스펜션 이미지 |

---
© 2025 HYUNDAI MOBIS
