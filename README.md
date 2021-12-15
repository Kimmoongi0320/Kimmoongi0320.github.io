# 유레카 Github 블로그 만들기
## 1. github에 블로그용 저장소 생성
1. 저장소의 이름을 Kimmoongi0320/Kimmoongi0320.github.io 로 생성
2. ruby와 jekyll를 설치

## 2. local 저장소 연동
1. git clone 기능을 통하여 로컬 저장소에 원격 저장소를 복사하여 가져온다.
## 3.블로그 생성
1.jekyll new . --force 을통해 현재 디렉토리에 Jekyll 뼈대 생성
2.bundle add webrick 으로 webrick 추가
3.git add, commit, push 으로 파일을 커밋한 후 원격 저장소로 푸쉬
4.깃헙 주소로 블로그 생성 확인

## 테마 적용하기
http://jekyllthemes.org/ 사이트의 What A Theme 테마 적용.
1. https://github.com/thedevslot/WhatATheme 에서 git clone을 사용하여 /home/git/bloggame/WhatATheme 경로로 받아옴.
2. 받아온 테마를 blog 폴더에 덮어쓰기를 하되, 의존성을 감안하여 _posts 폴더를 제외함.
3. 테마 파일들을 git으로 push함으로써 테마 적용

## 테마 수정하기
1. http://jekyllthemes.org/ 에서 적절한 테마 선택 후 깃헙 주소 클론
2. 클론한 깃헙 주고에 들어 있는 내용들을 자신의 저장소에 있는 _post와 겹치는 파일을 제외하고 덮어씌움(자신의 _post에는 이미 자신이 쓴 글이 있기 때문)
3. 덮어씌운 파일들을 git push를 통해 원격저장소로 푸쉬함.
4. 덮어씌운 파일 중 _config.yml 에서 각 이름,url,email 등의 값을 나의 저장소에 맞는 값으로 변경
5. 블로그에서 적용이 되었는지 확인

## post 글 작성
### "What is Git and Github" 포스터 작성
1. git bash를 통해 나의 로컬 저장소의 _post 파일로 이동
2. vi에디터를 통하여 글을 작성하고 댓글 기능을 넣기 위해 comments를 true로 지정해주었음.
3. 커밋한 후 원격저장소로 푸쉬 해줌
4. github블로그에서 정상적으로 생성되었는지 확인
