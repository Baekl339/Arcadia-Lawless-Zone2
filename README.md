# ARCADIA WASTELAND — 홈페이지 파일

## 업로드 방법 (기존 GitHub 저장소 유지)

1. 이 ZIP 파일을 압축 해제합니다.
2. 압축을 푼 `arcadia-lawless-zone` 폴더 안으로 들어갑니다.
3. `index.html`, `world.html`, `characters.html`, `assets` 폴더, `README.md`가 보이는 상태에서 **이 항목들을 전부 선택**합니다.
4. 기존 GitHub 저장소 `Baekl339/Arcadia-Lawless-Zone`의 최상위(root) 화면으로 이동합니다.
5. `Add file` → `Upload files`를 누릅니다.
6. 선택한 파일과 폴더를 업로드 영역에 끌어다 놓습니다.
7. 기존 파일과 같은 이름인 `index.html`, `assets/css/style.css` 등이 있으면 덮어씁니다.
8. 아래 `Commit changes`를 눌러 `main` 브랜치에 저장합니다.

**중요:** `arcadia-lawless-zone` 폴더 자체를 통째로 한 단계 더 넣지 말고, 폴더 안의 파일들을 저장소 최상위에 올려야 합니다. 저장소에 `index.html`이 바로 보여야 합니다.

## GitHub Pages 설정 확인

저장소의 `Settings` → `Pages`에서 Build and deployment가 `Deploy from a branch`, Branch가 `main`, Folder가 `/(root)`인지 확인합니다. 기존 설정이 이미 이렇다면 바꿀 필요 없습니다. 저장 후 배포가 완료되면 기존 GitHub Pages 주소에서 확인할 수 있습니다.

## 이미지 교체

- 캐릭터 사진은 `characters.html` 안의 각 `portrait-slot` 영역을 나중에 이미지 태그로 교체하면 됩니다. 현재는 빈 이미지 슬롯입니다.
- 지역 배경은 `assets/images/regions/` 안의 SVG 파일입니다. 같은 파일명을 유지하고 파일 내용을 바꾸면 사이트에 반영됩니다.
- 외부 폰트는 Google Fonts를 사용합니다. 인터넷 연결이 없으면 기본 글꼴로 표시됩니다.

## 구성

- `index.html` : 메인 페이지
- `world.html` : 세계관, 지역, 에테르, 세력
- `characters.html` : NPC 8명, 관계
- `assets/css/style.css` : 공통 디자인 및 반응형 스타일
- `assets/images/regions/` : 지역 및 메인 배경 일러스트(SVG)
