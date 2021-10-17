## Today I Learned

* git init : 저장소 설정, 처음만 하면 됨.

* **add**

  * 테이블 위에 올리기

    > ex) git add 원하는 것, git add . 은 현재 디렉토리 전체 저장

* **git status** 

  * add 후 상태 확인할때 사용

    * 새로 생성된것이 없을때

      > On branch master No commits yet

    * 커밋될 변경사항들

      > (staging area) Changes to be committed: (use "git rm --cached <file>..." to unstage)

    * ex) a.txt가 새로 생성되었을때

      > new file: a.txt

* **commit** 

  * 커밋 메세지 작성

    > ex) git commit -m '커밋메시지'

  * git log : 커밋 이력 확인

* **git remote add origin URL**
  * 저장소 설정, 한 사람당 하나

* **push** 

  * 버전 저장

    > ex) git push origin master

* **pull** 

  * 변경 사항 받아오기

    > ex) git pull origin master

  [깃허브 참고](https://chancoding.tistory.com/76) [타이포라 참고](https://gist.github.com/ninanung/73addc0263b34da5f021d2f02a356b7f) 