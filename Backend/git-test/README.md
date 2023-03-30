## Git Command

- `git init` : 깃을 시작함, 현재 디렉토리에 새로운 git repo 생성 
- `git remote add origin <remote repository url>`: 원격 저장소의 url을 지정함, 저장소 url을 origin이라는 명칭으로 설정했음
- `git add <file name>` add는 깃에 올리기 전에 스테이징을 하기 위한 커맨드로 올리고 싶은 파일명을 add 하면 깃에 커밋할 준비가 된 파일을 임시로 저장함 
- `git commit` add로 스테이징한 파일들을 커밋함 , 저장소에 저장됨 
- `git push origin <branch name>` 현재 위치에서의 커밋을 원격저장소에 올림, 올리고 싶은 브랜치 명으로 업로드함 
- `git pull origin <branch name>` 원격 저장소에 저장된것을 로컬 저장소로 가져옴, 원격저장소 내의 있는 가져오고 싶은 브랜치 명으로 가져옴 
- `git merge <branch name>` 현재 브랜치와 다른 브랜치를 병합함. git merge <합치고 싶은 다른 브랜치 이름>