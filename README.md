# TODO.md

### TODO.md는 무엇?

> What is TODO.md?

- TODO.md 형식은 GFM - GitHub Flavored Markdown - Task Lists 를 기반으로 합니다.
- TODO.md는 여러 섹션으로 구성된 작업이 포함된 파일입니다.
- TODO.md의 작업은 섹션이 보드의 열이 되는 칸반 보드를 사용하여 시각화할 수 있습니다 .
- 변경 내역 유지 에서 영감을 얻을 수 있습니다.

### TODO.md를 유지하는 이유는?

> Why keep a TODO.md?

프로젝트에는 문서, 이슈 포럼, Wiki 페이지 등과 같은 다양한 정보 소스가 있습니다. 현재 진행 상황을 파악하기는 어려울 수 있습니다.

TODO.md 파일을 보관하면 프로젝트 계획과 수행해야 할 작업에 대해 알고 싶은 사람이 더 쉽게 알 수 있습니다.

### 온라인 관리 도구를 사용하지 않는 이유는?

> Why not using online management tools?

종종 새 프로젝트는 신속하게 수행해야 할 작업의 개요를 설명하는 작업 목록으로 시작됩니다.

일부 온라인 도구는 대규모 프로젝트를 효율적으로 관리하는 데 유용하지만 초기 단계에서 사용하면 소규모 프로젝트에 더 많은 노력과 오버헤드가 추가됩니다.

다음과 같은 몇 가지 다른 이유

> 이식 가능한 일반 텍스트 형식, 동일한 프로젝트 디렉터리, 오프라인 작업, 개인 정보 보호, 버전 관리(git 사용), 미니멀리스트 도구 등

### TODO.md 형식

> TODO.md format

- TODO.md에는 여러 열이 있습니다.
  - TODO.md can have multiple columns.
- 각 열에는 체크박스 기호 `- [ ]`나 하이픈 으로 시작하는 작업이 있습니다. `-`
  - Each column has tasks that start with a checkbox sign `- [ ]` or just a hyphen `- `
- 완성된 열 이름에는 ✓또는 이 포함되어야 합니다 `[x]``.
  - Completed column name must contain `✓` or `[x]`.
- Github 페이지에서 줄 바꿈 역할을 하기 위해 모든 작업 제목 끝에 "2개의 공백"이 있습니다.
  - There are "2 spaces" at the end of every task title to serve as line breaks on Github pages.
- 작업 제목 끝에 태그, 멘션, 견적, 날짜 시간, 티켓 ID 등을 입력할 수 있습니다.
  - Tags, mentions, estimates, date time, ticket id, etc. can be entered at the end of the task title.
- 제목에 공백 2개가 있는 작업은 하위 작업 또는 설명입니다.
  - A task with 2 space indentation in the title is a sub-task or description.

```
# Project Name
Project Description

### Column Name
- [ ] Task title ~3d #type @name yyyy-mm-dd
  - [ ] Sub-task or description

### Completed Column ✓
- [x] Completed task title
```

- 확인란은 GFM - GitHub Flavored Markdown - 작업 목록 에 설명된 대로 사용되지만 선택 사항입니다.
- 확인란이 없는 작업 목록은 다음과 같습니다.

```
### Column Name
- Task title ~3d #type @name yyyy-mm-dd
  - Sub-task or description

### Completed Column ✓
- Completed task title
```

### 추가 사항

- [An example of TODO.md](TODO.md)
- [Vscode Kanban Extension](https://bit.ly/2JcrUWJ)
