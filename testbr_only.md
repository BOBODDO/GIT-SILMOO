#testbr 브랜치에만 생성한 파일입니다.

이걸 master 브랜치에 git merge --no-ff testbr 명령어를 통해 파일을 가져와 볼 예정입니다!

## master 로 한번 merge 한 이후에 작업
### 222
### 333
### 444
### 555

## git reset --hard와 --soft 의 차이를 깨닳았다!
### git reset --hard
> 소스까지 완전히 되돌리고 싶을 때

### git reset --soft
> staging > commit 으로 이동했던 것을 되돌릴때 (단, 소스는 그대로 유자)
> reset --soft 이후에, reset HEAD 명령어를 통하여 staging애서 working(VSCODE에서 -을 클릭해서 이전 단계로 후퇴한 것과 동일)으로 이동 가능하다

## git tag
> git tag v0.0.1 
위 명령어를 통해 태그를 지정 가능하다(릴리즈 단위)
> git push origin v0.0.1
위 명령어를 통해 github 서버에 태그를 지정 가능하다(릴리즈 단위)
