## 만든 버전 GitHub에 올리기 
git remote add / git push
내 컴퓨터 프로젝트 폴더에 GitHub 저장소 주소 알려주기 (git remote add)
내 컴퓨터에 만들었던 덩어리 GitHub에 올리기 (git push)

## 로컬 저장소와 원격 저장소
로컬 저장소는 내 컴퓨터에서만 하는 것이기 때문에 다른 사람들과 함께 버전관리를 하려면 원격저장소에 올려야함
그렇게 원격저장소에 올리는 명령어가 push임

## 원격 저장소 GitHub에서 만들고 커밋 푸시하기
1. GitHub에 로그인해서 Boxiting 저장소 생성
2. 내 컴퓨터 jj-cat 폴더에 GitHub 저장소 주소 알려주기 (git remote add origin https://github.com/아이디/이름.git) origin 은 올릴 이름임 remote이름 
3. 만든 커밋 푸시하기 (git push origin master) origin = 리모트 / master = 브랜치
4. GitHub 사이트에서 올라간 커밋 확인

## git repository 생성할때
.gitignore : 올리고 싶지 않은 파일을 적으면 저장소에 안올라감 (보안에 취약한 거를 안올릴때 사용)
.license : 이 오픈소스를 어디까지 사용할껀가 허용범위 같은느낌
