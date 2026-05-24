# 굿모닝 리셋 페이지 배포 가이드

이 저장소는 정적 파일(`index.html`) 기반의 아침 기상 큐레이션 페이지입니다.

## GitHub Pages로 배포하기

1. 기본 브랜치를 `main`으로 설정합니다.
2. 저장소의 **Settings → Pages → Build and deployment**에서 Source를 **GitHub Actions**로 선택합니다.
3. 이 저장소에 push하면 `.github/workflows/deploy-pages.yml` 워크플로가 실행되어 자동 배포됩니다.
4. 배포 완료 후 Actions 로그의 `page_url` 또는 Pages 설정 화면에서 배포 URL을 확인합니다.

## 로컬 미리보기

브라우저에서 `index.html`을 직접 열어 확인할 수 있습니다.
