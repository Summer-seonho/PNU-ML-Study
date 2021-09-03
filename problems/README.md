# 이용방법
 코드리뷰와 풀이과정 확인을 위해 Pull Request로 제출하지만, github에서 직접 업로드해도 됩니다.
 
 ## 준비사항
 * (필수) git 설치: [바로가기](https://git-scm.com/download/win)
 * (옵션) git GUI 도구: sourcetree, Github Desktop 등  

 git 설치 후 로컬에 git 저장소를 불러옵니다. (clone)
  > (Git CLI)  
  > cd <원하는 폴더>  
  > git clone https://github.com/Cotidie/PNU-ML-Study.git  
  > cd PNU-ML-Study
 
 ## Pull Request
  Git CLI(Git Bash) 기준입니다.   
1. 먼저 원격 저장소(Github)와 동기화합니다.  
```bash
> git checkout main      # main 브랜치로 이동합니다.
> git pull               # 원격저장소의 main 브랜치와 동기화합니다.
```
2. main 브랜치로부터 자신의 브랜치를 만듭니다.  
```bash
> git checkout -b <원하는 이름>    # <원하는 이름> 브랜치를 새로 만들고, 그곳으로 이동합니다.
```
3. 문제풀이 파일을 본인이름 폴더에 넣은 후 커밋합니다.  
 *ex) 1주차 : /problems/01/<본인이름>/<답안파일>*
```bash
> git add .                       # 현재 폴더의 모든 변경내역을 커밋 대상으로 만듭니다.
> git commit -m "작성할 메시지"    # 커밋 대상들을 커밋합니다.
```
4. 원격 저장소에 업로드합니다.  
```bash
> git push          # 원격 저장소에 업로드합니다.
```
:exclamation: 브랜치 생성 후 첫 push라면 다음 명령어를 이용해야 합니다.
```bash
# 원격저장소(origin)의 <브랜치명> 브랜치와 로컬의 현재 브랜치를 연동
# 이때, 원격저장소에 해당 브랜치가 없다면 자동으로 생성된다.
> git push -u origin <브랜치명>
```
5. Github > Pull Requests > New pull request를 통해 본인 브랜치를 master 브랜치로 Pull Request 합니다.
![Pull Request](https://i.imgur.com/zvgXoaQ.png)
	
 ## 직접 업로드
  Github에서 바로 add files > upload files로 올릴 수 있습니다.
	
