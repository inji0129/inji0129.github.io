# 지인 이력서

GitHub Pages / Jekyll 기반 공개 백엔드 이력서. 소개와 기술 스택을 상단에 두고, 회사별 핵심 성과를 간결한 목록으로 표시합니다.

## 편집

- `_data/general.json`: `intro`, `skill_groups`, 회사별 `highlights`가 공개 화면에 사용됩니다. `works`는 상세 작업 근거를 보존합니다.
- `_layouts/general.html`: 현재 공개 레이아웃
- `assets/resume.css`: 화면·모바일·인쇄 스타일
- `assets/지인_이력서.pdf`: 공개 다운로드 PDF

`detailed/`와 `designs/`의 기존 자료는 유지합니다.

## 인쇄

상단 인쇄 버튼에서 A4, 배율 100%, 머리글·바닥글 끄기, 배경 그래픽 켜기를 권장합니다. 화면과 PDF는 같은 데이터·스타일을 사용하며 인쇄 시 회사 단위 페이지 구성을 적용합니다.

## 배포

main 브랜치 루트의 GitHub Pages Jekyll 빌드를 사용합니다. 내부 코드·비밀값·검토용 자료는 게시하지 않습니다.


## Language versions

- Korean: `/`
- English: `/en/`
- Each page links to its matching PDF in `/assets/`.
- Build sources: `output/general/build_clean.py`, `output/general-en/build.py`, then `output/general-en/publish_web.py` in the authoring workspace.
- English content is retained in `_data/general_en.json`; `/en/index.html` is generated static HTML.
