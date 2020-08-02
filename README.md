## Android Developer 과제 안내
1. toss-android-bot/next-developer-2020 저장소를 본인의 컴퓨터에 clone 합니다.
    ```
    $ git clone git@github.com:toss-android-bot/next-developer-2020.git
    ```

2. 아래 명령어를 실행하여 지원자의 정보를 담은 Author 파일을 생성하고 commit합니다.
    ```
    $ echo "이름 이메일" > Author  # 지원자의 이름과 이메일을 입력해주세요.
    $ git add Author
    $ git commit -m "Add Author"
    ```
    
3. https://github.com/new 에서 'next-developer-2020'라는 이름으로 **private repository** 를 생성합니다.
    > public repository가 아닌 private repository라는 점에 주의해주세요.
    > 지원자님의 gitgub 계정으로 생성해주세요.

4. 아래 명령어로 origin 을 변경하고, 지원자의 저장소에 push 해주세요.
    ```
    $ git remove origin
    $ git add origin git@github.com:{github-nickname}/next-developer-2020.git
    $ git add puhs origin
    ```
    
5. 지원자님이 생성한 repository 설정에서 **'toss-android-bot'** 을 **Collaborator**로 추가해주세요.
    > https://github.com/{github-nickname}/next-developer-2020/settings/access<br>
    > 위 링크에 접속하여 'Invite a collaborator'를 눌러 'toss-android-bot'을 추가해주세요.
    
6. clone 받은 repository에 있는 안드로이드 프로젝트가 지원자님의 컴퓨터에서 빌드가 성공하는지 미리 확인해주세요.

7. 8월 8일 토요일 오후 2시에 발송되는 과제를 90분 이내에 해결하시고, 지원자님의 repository에 push 해주세요.<br>
    최종 commit 시간을 기준으로 90분을 넘지 않아야 함을 주의해주세요.
