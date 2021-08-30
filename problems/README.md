# 이용방법
 코드리뷰와 문제풀이 확인을 위해 Pull Request로 제출하지만, Git에 아직 익숙치 않다면 직접 업로드해도 됩니다.
 
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
> git checkout master
> git pull  
```
3. master 브랜치로부터 자신의 브랜치를 만듭니다.  
```bash
> git checkout -b <원하는 이름>  
```
4. 문제풀이 파일을 본인이름 폴더에 넣은 후 커밋합니다.  
 *ex) 1주차 : /problems/01/<본인이름>/<답안파일>*
```bash
> git add .  
> git commit -m "작성할 메시지"  
```
5. 원격 저장소에 업로드합니다.  
```bash
> git push  
```
6. Github > Pull Requests > New pull request를 통해 본인 브랜치를 master 브랜치로 Pull Request 합니다.
![Pull Request](https://i.imgur.com/zvgXoaQ.png)
	
 ## 직접 업로드
  위 과정이 귀찮거나 익숙치 않다면 Github에서 바로 add files > upload files로 올려주시면 됩니다.
	
