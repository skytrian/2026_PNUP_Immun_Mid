# Immunology Midterm Study

면역학 중간고사 복습용 퀴즈 페이지입니다.

## 사용
GitHub Pages 배포 주소에서 `index.html`을 열어 객관식 및 개념 복습 문항을 풉니다.

## 버전 규칙
페이지 버전은 `YYYY.MM.DD.MAJOR.MINOR` 형식입니다.
- `YYYY.MM.DD`: 배포 날짜
- `MAJOR`: 큰 구조 변경 또는 호환성에 영향을 주는 변경
- `MINOR`: 문항 수정, 기능 추가, 오류 수정

HTML의 `data-app-version` 속성과 `APP_VERSION` 상수는 항상 같은 값으로 유지합니다. 수정 배포 시 두 값을 함께 올립니다.

## 캐시 및 자동 새로고침
페이지는 배포된 HTML을 캐시 방지 쿼리로 다시 확인하고, 버전이 달라지면 새 버전 쿼리를 포함한 URL로 이동합니다. 새 배포 직후 GitHub Pages/CDN 반영까지 잠시 시간이 걸릴 수 있습니다.
