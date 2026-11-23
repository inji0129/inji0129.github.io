# 지인 이력서
Jekyll 기반 GitHub Pages 이력서. 화면 우측 `PDF로 저장` 또는 브라우저 인쇄를 사용합니다.

## 내용 수정
`_data/resume.json`의 회사·프로젝트·성과를 수정하면 Jekyll이 자동 반영합니다. 상단 소개는 `_includes/resume.html`, 디자인과 인쇄 설정은 `assets/style.css`에서 수정합니다.

## 로컬 실행
`bundle install`, `bundle exec jekyll serve` 후 localhost:4000을 엽니다.

## PDF 저장
A4, 배율 100%, 브라우저 머리글/바닥글 해제, 배경 그래픽 켜기를 권장합니다. 출력에서 탐색과 버튼은 제외되고 프로젝트가 중간에서 갈라지지 않도록 설정했습니다.

## 게시
GitHub Pages의 main 브랜치 루트 Jekyll 빌드 방식으로 게시합니다. 내부 소스·설정·이력 검토 자료는 이 저장소에 포함하지 않습니다.
