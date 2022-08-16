# 배운 내용 정리

```
파일 만들기 - touch.{filename}
파일 지우기 - rm {filename}
폴더 지우기 - rm -f {filename}
모두 지우기 - rm *
조건으로 모두 지우기 - rm *{조건} or rm {조건}*

파일 수정하기 - vi filename
:q - quit
:q! - quit without save changes
:wq - wirte and save changes
```

1. 순서가 있는 경우 앞에 숫자 입력
2. 이렇게 하면 됨

- 순서가 없는 경우
	- 이런 식으로

<!--수평선-->

# git object
Blob : 파일 하나의 내용에 대한 정보
Tree : Blob나 subtree의 메타데이터(디렉토리 위치, 속성 등)
Commit : 커밋 순간의 스냅샷

# git 환경구축
- git 설치 확인: git -v
- git 환경설정
  - git config --global user.name "user name"
  - git config --global user.eamail "user email"
  - git config --global core.editor "vim"
  - git config --global core.pager "cat"

- git config --list로 설정 확인 가능

- 하면 좋은 설정 : 
git config --global alias.lg "log --color --graph --
pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"

1. Start project with git clone
2. git add
3. git commit
4. git push

## git convention
feat: Add server.py  
fix: Fix Typo server.py  
docs: Add README.md, LICENSE  
conf: Create .env, .gitignore, dockerfile  
BREAKING CHANGE: Drop Support /api/v1  
refactor: Refactor user classes  

## first push
1. git push origin main
2. git token 입력



