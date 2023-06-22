# <strong>Git Manual</strong>

***

### Git branch
- git branch "branch_name"  
  - 새로운 branch 생성  

- git checkout -b "branch_name"  
  - 새로운 branch 생성과 동시에 해당 branch로 checkout 
- git branch -D "branch_name"  
  - 해당 branch 삭제
- git checkout "branch_name"
  - 해당 branch로 이동
- git branch
  - 현재 등록된 branch 조회

***

### Git에서 유실된 commit 복원하는 방법
- git reflog
  - git reference log(로그 참조)
- git reset --hard "commitID"
  -  유실된 커밋을 주체로 돌려놓는 방법
- git cherry-pick "commitID"
  - 유실된 커밋만 현재 브랜치로 가져오는 방법

***

### Git 변경 내역 오려두는 방법
-git stash
  - 변경된 내역/파일 전체를 잠시 오려두는 방법
-git stash pop
  - git stash했던 내역/파일을 다시 원래대로 pop하는 방법
