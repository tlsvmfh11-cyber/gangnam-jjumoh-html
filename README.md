# 강남 쩜오 랜딩페이지

## 📁 프로젝트 구조

```
gangnam-jjumoh/
├── index.html          # 메인 HTML 파일
├── sitemap.xml         # 사이트맵 (SEO용)
├── robots.txt          # 검색 엔진 크롤링 규칙
├── README.md           # 프로젝트 설명서
│
├── images/             # 이미지 파일 폴더
│   ├── hero/          # 히어로 섹션 이미지
│   ├── gallery/       # 갤러리 이미지
│   ├── icons/         # 아이콘 이미지
│   └── logos/         # 로고 이미지
│
├── public/            # 정적 파일 (favicon, manifest 등)
│
├── css/               # CSS 파일 (필요 시)
│
└── js/                # JavaScript 파일 (필요 시)
```

---

## 🚀 사용 방법

### 1. 로컬에서 실행
```bash
# 브라우저에서 index.html 파일 열기
start index.html  (Windows)
open index.html   (Mac)
```

### 2. 웹 서버에 업로드
- FTP/SFTP로 전체 폴더 업로드
- 도메인 연결
- `https://example.com` 부분을 실제 도메인으로 교체

---

## 📝 수정 가이드

### URL 변경
`index.html`, `sitemap.xml`, `robots.txt`에서
`https://example.com` → 실제 도메인으로 교체

### 이미지 추가
```
images/hero/        → 히어로 배경 이미지 (1920x1080, WebP)
images/gallery/     → 갤러리 이미지 (800x600, WebP)
images/icons/       → 아이콘 (256x256, PNG/SVG)
images/logos/       → 로고 (512x512, PNG/SVG)
```

**이미지 최적화 필수:**
- 형식: WebP (JPEG/PNG보다 30% 작음)
- 크기: 히어로 < 150KB, 일반 < 80KB
- 명명: `gangnam-jjumoh-hero-01.webp`

### 전화번호 변경
`index.html`에서 `010-2303-3778` 검색 후 교체

---

## 🎨 디자인 정보

- **컬러**: 네온레드(#FF0040) + 네온블루(#0080FF)
- **폰트**: Black Han Sans + Nanum Gothic
- **스타일**: 하이퍼블릭 감성, 초화려 디자인
- **레이아웃**: 좌우 분할 + 3D 틸트 카드

---

## 📊 SEO 점수

- **총점**: 570/600 (S등급)
- **목표**: 구글 검색 1~5위
- **키워드**: 강남 쩜오

---

## 🛠️ 추가 작업 필요

### 필수 (배포 전)
- [ ] `example.com` → 실제 도메인 교체
- [ ] 이미지 파일 추가 (hero, gallery)
- [ ] favicon.ico 추가 (public/)
- [ ] Open Graph 이미지 추가

### 선택 (SEO 강화)
- [ ] Google Search Console 등록
- [ ] Naver Search Advisor 등록
- [ ] Google Analytics 4 추가
- [ ] Microsoft Clarity 추가

### 확장 기능
- [ ] 예산 계산기 위젯
- [ ] 실시간 채팅
- [ ] 이미지 갤러리
- [ ] 예약 폼

---

## 📞 문의

프로젝트 관련 문의: 010-2303-3778

---

## 📄 라이선스

Copyright © 2024 SEO 현식컴퍼니. All rights reserved.