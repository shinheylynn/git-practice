## Git Command

- `git init` : git 저장소 생성 명령어 - clone을 활용한 게 아니라 최초로 git 저장소를 생성한 경우 소스 코드 파일을 git으로 관리하기 위해서 git 저장소를 초기화시키는 명령어
- `git remote add origin <remote repository url>` - 내 로컬 저장소와 원격 저장소 (url)를 remote로 연결해 관리하겠다는 명령어
- `git add <file name>` : 수정사항이 있는 파일 내역을 추가하겠다는 뜻. Commit & Push를 하기 전에 stage에 올리는 것과 같다.
- `git commit` : push하기 전에 commit 명령어를 통해 기록을 남긴다.
- `git push origin <branch name>` - 로컬 저장소에서 만든 브랜치의 내역을 원격 저장소에 올리는 명령어
- `git pull origin <branch name>` - 원격 저장소에 있는 브랜치를 로컬 저장소로 받아오는 명령어
- `git merge <branch name>` - 현재 브랜치에 다른 브랜치의 수정사항을 병합시키는 명령어
