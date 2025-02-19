# 개발에 필요한 문서
-  기능 정의서 > 모든 기능에 대한 정의 (엑셀)
-  정책 정의서 > 보안,권한에 대한 정의 (엑셀)
-  일정 산출표 > 기획,디자인,퍼블리싱,개발간에 일정계획,조율,지라(jira)
-  화면 정의서 > UI, 퍼블리싱, 개발(기능)에 대한 요소가 다 들어있음

### 랜딩페이지 > 홍보, 마게팅, 요소의 배치보다는 정보에 신경
### 쇼핑몰 > 회원, 상품 관리자와 같은 페이지들이 존재(기능,정책에 신경을 써야함)
### 플랫폼 > 개인대개인, 개인대 기업, 기업대 개인간의 연결
### 포털사이트 > 정보의 양이 많아야함, 위의 기능이 다 있어야 함

# GIT 기본 용어
### 작업공간 (working directory / working tree)
- 작업을 하는 공간
- 로컬 저장소에 접근하여 파일을 생성, 수정 그리고 저장하는 공간
### 임시 작업공간 (stage area)
- working tree -> stage 로 옮기다고 함
### repository 실질적으로 저장되고 기록되는 공간
- 저장소
- 히스토리, 태그, 소스의 가지치기 혹은 branch 에 따라  버전을 저장
- 작업자가 변경한 모든 히스토리를 확인 가능
```
git(local)               |                 git hub
git -> 폴더(working tree) -- (uploard) --> stage area -- (확인 commit) -> repository
```
### git
- 인터넷 없이도 작업가능함
### commmit
- 현재 변경된 작업 상태를 점검을 마치고 확정하고 저장소에 저장하는 작업
### barnch
- 가지 또는 분기점
- 작업을 할때에 현재 상태를 복사하여 branch 에서 작업을 한 후에 완전하다 싶을때 merge 를 하여 작업한다
- 새로 만든 branch는 지금 작업하고 있는 마지막 commit 을 가르킨다
### Merge
- 다른 branch의 내용을 현재 branch로 가져와 합치는 작업을 의미한다
### git init
```
git 저장소를 초기화 ( not reset, 초기값 지정)
저장소나 디텍토리 안에서 이 명령어를 실행하기 전 까지는 그냥 일반 폴더이다
이 명령어를 입력한 후에야 추가적인 git 명령어 입력 가능
```
1. 아무 폴더나 만들고 폴더 내부를 오른쪽 클릭하여 git bash 실행
2. git init 입력하면 git 이라는 폴더 생성되며 git 이 폴더 관리

### git status
```
저장소 상태체크
어떤 파일이 저장소 안에 있는지 commit이 필요한 변경사항이 있는지
현재 저장소의 어ㅏ떤 branch에서 작업하고 있는지 등의 상태 정보 출력
```

- git config -- global user.name
- git config -- global user.email
- git daa . (. or -A)
- git commit -m "커밋데이터"
- git branch "새로운브랜치"
- git checkout "옮길브랜치"
- git remote origin "깃주소"
- git push -u "origin master"
