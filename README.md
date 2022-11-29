Git blog 만들기!
1. username.github.io 이름으로 Github에서 repo를 생성합니다.
2. 내 컴퓨터에 git_blog 폴더를 만들고, cmd(리눅스는 터미널)에서 git_blog폴더로 이동한 뒤, Github의 원격 저장소 주소를 복사해서, 내 로컬 저장소에 clone 합니다!
3. git status로 현재상태 확인 -> git add로 변경파일을 추가 -> git commit -m "입력할 메세지"로 커밋 -> git push로 원격 저장소에 업로드 (github에서 Setting에 들어가, token을 생성하고 Password를 입력해야합니다)
4. github에서 username.github.io 저장소로 들어가서 Setting에 들어가서 pages에 들어가서 Source에서 Branch를 main으로 해주고 save를 눌러줍니다.
잠깐 기다리면 바로 위 GitHub Pages에 내 저장소 이름이 url로 된 사이트가 완성됩니다.

테마 입히기 !
1. username.github.io 이름으로 원격 저장소를 다시 만든 뒤, 원하는 테마의 원격 저장소에서 fork해서 username.github.io로 가져옵니다.
2. cmd(리눅스는 터미널)에서 git_blog폴더에서 Git blog를 만들때 했던 작업을 똑같이 해줍니다.

내용을 바꾸고 싶을땐 _posts파일에서 내용을 수정합니다.
