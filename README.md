# Jayyeong Jeong

React 기반 웹 서비스를 만드는 프론트엔드 개발자입니다. 비개발자의 요청을 화면과 기능으로 구체화하고, 이미지가 많은 전시 웹사이트와 API 연동 화면을 구현하며 배포까지 연결하는 작업에 관심이 있습니다.

## 대표 프로젝트 · KUAD 2026 ALTER EGO

건국대학교 의상디자인학과 졸업전시 웹사이트입니다. 전시 콘텐츠, 룩북·런웨이 이미지, 굿즈 주문 화면과 관리자 주문 관리 UI를 다룹니다.

**[프로젝트 소개 및 코드](https://github.com/jayyeong/ALTEREGO_2026_VITE) · [사이트](https://www.kuadarchive.com/2026/) · [개선 기록: 런웨이 갤러리 PR #27](https://github.com/jayyeong/ALTEREGO_2026_VITE/pull/27)**

| 확인할 수 있는 작업 | 구현 근거 |
| --- | --- |
| 이미지 로딩 개선 | [런웨이 갤러리](https://github.com/jayyeong/ALTEREGO_2026_VITE/blob/main/src/pages/Runway.jsx): 썸네일·원본 분리, 지연 로딩, 모달의 방향키·ESC 조작 |
| 주문 및 운영 화면 | [주문서](https://github.com/jayyeong/ALTEREGO_2026_VITE/blob/main/src/pages/CheckoutPage.jsx), [관리자 대시보드](https://github.com/jayyeong/ALTEREGO_2026_VITE/blob/main/src/pages/AdminDashboard.jsx): 입력 검증, API 연동, 입금 상태·품절 관리, 엑셀 다운로드 |
| 배포 자동화 | [GitHub Actions](https://github.com/jayyeong/ALTEREGO_2026_VITE/blob/main/.github/workflows/deploy.yml): 빌드 → S3 업로드 → CloudFront 캐시 무효화 |

현재 `main`에서 스토어·주문 경로는 종료 안내 화면으로 연결됩니다. 주문 관련 구현은 소스에서 확인할 수 있으며, 관리자 기능은 별도 API가 필요합니다. 이 저장소의 공개 범위는 프론트엔드와 배포 설정입니다.

## 기술과 경험

- **대표 프로젝트에서 확인 가능:** React, JavaScript, React Router, Tailwind CSS, Vite, REST API 연동, AWS S3·CloudFront, GitHub Actions
- **그 외 경험:** Spring Boot, JPA, MySQL, Python, OpenCV, YOLOv8 모델 학습  
  위 기술은 경험 소개이며, 대표 프로젝트의 공개 프론트엔드 코드와는 구분합니다.

## Links

- Blog: [aia1235.tistory.com](https://aia1235.tistory.com/)
- 이전 CRA 구현: [ALTEREGO_2026](https://github.com/jayyeong/ALTEREGO_2026) — 현재 대표 프로젝트는 Vite 저장소입니다.
