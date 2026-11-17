# 저장소 정보 (`carcallnote-policy`)

## 빌드 및 검증
- 정적 HTML 문서(`index.html`, `privacy-policy.html`) 전용 저장소로 별도 빌드 과정이 없다.
- 변경 시 HTML 문법 및 필수 법적 고지(상호, 대표자, 사업자등록번호, 통신판매업신고번호, 주소, 문의 이메일) 포함 여부를 확인한다.

## 배포 방식
- `main` 브랜치 루트(`/`)가 GitHub Pages(`legacy` 빌드)를 통해 자동 배포된다.

## 배포 확인 방법
- PR 병합 후 아래 두 주소가 `HTTP 200`으로 응답하고 최신 본문이 노출되는지 확인한다:
  - 공식 안내 페이지: `https://innoaz2020-stack.github.io/carcallnote-policy/`
  - 개인정보처리방침: `https://innoaz2020-stack.github.io/carcallnote-policy/privacy-policy.html`
