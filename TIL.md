# 형상관리 시스템
## Answer 1
***
: 작업물 제작시 업데이트 버전마다 상태를 저장하고 손쉽게 이전 작업상태로 돌아가는 방법을 제공하기 때문이다

## Answer 2
***
 : git은 분산 버전 관리 시스템이고, 버전 관리를 할 때, 자신의 컴퓨터와 원격지 서버에 모두 버전 관리를 할 수 있다.   
 먼저 git은 코딩을 하다보면 실수할 수도 있기 때문에 이전의 버전으로 돌아가기 위해서 쓴다.  
 다음으로 새로운 버전을 실험해 볼 수 있기 때문에도 쓰며, 다른 팀원들과 같이 하기 위해 공유가 필요한 경우에 사용된다.
 
 ## Answer 3
 ***
: git은 버전 관리 시스템이고,github는 프로젝트를 올리고, 공유할 수 있는 사이트이다.

 
 ## Answer 4
 ***
1. `git clone`: 전체를 다 가져오는 명령
>`git clone [원격저장소주소] [directory]`

2. `git add`: 파일을 추가하는 것
>`git add [directory]
    git add .`
3. `commit`: 변경사항을 기록한다는 명령(?)
>`git commit -m "commit message"`
4. `push`: commit한 변경사항을 업데이트하여 반영하는 것
>`  git push -u origin [branch name(main)] `
5. `pull`: 가져와서 같은 branch를 합쳐버리는 명령
>`git pull origin [branch name(main)]`
6. `branch`: test를 위한 새로운 갈래를 만들어서 test를 실행하는 것 
7. `stash`: git 저장소의 변경사항을 임시로 저장하는 것
>`git stash`  
`git stash save`
## Answer 5
***
1. `object` : git에서 변경사항을 추적하기 위해 사용한다.
2. `commit` : repository의 현재 상태를 가지고 있다. directory와 파일의 상태를 기록하고 있는 tree object를 가리킨다.
3. `Head` : 현재 활성화된 Branch
4. `Branch` : test를 위한 새로운 갈래를 만들어서 test를 실행하는 것 
5. `Tag` : commit에 태그를 다는 것. release할 때 사용된다.

 + ` git reset --hard <돌아갈 commit>`  
 `git push -f`
## Answer 6 
***
`git log --oneline`  

`git revert <취소할 커밋>`   

`git commit -m "revert message"`  
 
`push`

