## 설명파일
* git init 명령어로 초기화 함. 
* git config 명령어로 설정 
* $git config --global --unset user.email. "ddoddoja@gamil.com"
* $git add readme.me : readme.md 파일만 stage 상태로 변경함. 
* $git status : 현재 상태 알려줌. 
* $git rm --cached readme.md
* $git commit -m 'readme.me 추가'
* $ git log : commit history 확인
* $ git push -u origin master : 원격저장소에 올리기 / 브라우저 인증 또는 Token 입력하기
* 403 오류 난다면 $ git config credential.username "usename" / $ git config credential.useremail "email"
* $ git branch -a : 모든 branch 목록 확인하기
* $ git remote -v : 원격 저장소 정보 확인하기 or $ git config remote.origin.url 
* MyApp-Raccon 폴더를 생성하고 