# Unity Custom Package Template
## 저장소 이름
- 접두사로 `unitypackage` 사용
- 단어 구분은 `-`로 통일
- 전부 소문자로 작성
- 예시 : unitypackage-game-manager

## 수정 필요 파일
- README.md
  - 전부 지우시고 새로 작성해주세요
- package.json
  - "name": "com.eu4ng.`category`.`package-name`"
  - "displayName": "`Package Name`"
  - "category": "`Category`",
  - "description": "패키지 설명"

## 폴더 구조
Root
- Editor
  - Eu4ng.`Category`.`PackageName`.Editor.asmdef
- Runtime
  - Eu4ng.`Category`.`PackageName`.asmdef
- Tests
  - Editor
    - Eu4ng.`Category`.`PackageName`.EditorTests.asmdef
  - Runtime
    - Eu4ng.`Category`.`PackageName`.Tests.asmdef
- Documentation (옵션)
  - ClassDiagram.drawio
  - ClassDiagram.png
  - FlowChart.drawio
  - FlowChart.png

