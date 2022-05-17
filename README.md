# quick-git-practice
This is a quick example about the basics of Git and GitHub.

Here are the participants:
 * Andrei
 * Jia Son
 * Dasom
 * yuna
 * git : https://www.youtube.com/watch?v=FXDjmsiv8fI
 * study: https://www.youtube.com/watch?v=nhNq2kIvi9s

## Markdown
Do you see the `.md` at the end of this filename (`README.md`)? That's a file extension called `Markdown`. It's an easy way to format text. Like HTML but easier and more readable. Please search for a `github markdown cheatsheet` or the equivalent 한글 term.

### Markdown Headings
# Heading 1 (equivalent to `<h1>Heading1</h1>`)
## Heading 2 (equivalent to `<h2>Heading2</h2>`)
### Heading 3 (equivalent to `<h3>Heading3</h3>`)
#### Heading 4

### Markdown Tables
Markdown makes it easy to create tables

| Column A | Column B |
|--|--|
| Yes | No |
| `true` | `false`|

| Column C | Column D |
|--|--|
| Yes | No |
| `true` | `false`|

| Column C | Column D |
|--|--|
| Yes | No |
| `true` | `false`|


## Git Commands

* git 폴더 생성
  * `$ git init`
* 백업할 파일들 전부 선택
  * `$ git add -A`
* 이 시점까지 이런 작업 진행
  * `$ git commit -m <작업수행 내용>`
* commit해서 박제 / 각 버전의 변경사항들만 기록되는 거라 박제를 여러번해도 용량을 몇 배로 차지하지 않음
* 프로젝트 로그 확인
  * `$ git logs` 
* 박제된 과거의 상태로 복원⚠️
  * `$ git reset —hard <3r8a0>`
* 분기상황에서 사용: 주가되는 내용은 메인 브랜치에서 작업
  * `$ git branch <newbranch>`
* 적용해도 되겠다 싶으면 브랜치 합침
  * `$ git merge <newbranch>`

code
