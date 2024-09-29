# Git / Github 실습

github 주소: https://github.com/bhoon716/web_study.git

---

1. VS Code에서 원하는 폴더 열기
2. Ctrl + ` 로 터미널 열기 -> 터미널 우측 상단의 '+' 버튼 옆의 화살표 눌러서 Git Bash 열기
3. 아래 명령어 차례대로 입력

```Bash
git init
git remote add origin https://github.com/bhoon716/web_study.git
git branch -M main
git pull origin main
```

4. 이후 각자 '브랜치' 생성 후 init.html파일을 아래처럼 작성

> 이름: 하고 싶은 말 | 이름2: 댓글 | 이름3: 댓글 | ....

> ex) 병훈: 반갑슴다 | 재훈: ㅎㅇ

다른 사람 글의 줄과 같은 줄에 댓글 남겨서 의도적으로 충돌 발생 >> 각자 해결

5. push 후 github에 들어가서 본인 브랜치에 대해 main 브랜치로 Pull Request 요청 & #스터디-git 슬랙에 메시지 남기기

6. 최소 2번 이상 실습 권장

---

커밋 메시지는 다른 사람들도 알아볼 수 있도록 잘 작성해주세요.

모르는 부분 언제나 질문해주세요.

---

##### .html 파일 실행하는 법

1. VS Code Extension에서 'Live Server' 설치 -> html 코드 창에서 우클릭 -> Open With Live Server -> 브라우저 자동으로 열림, 파일 변경 후 저장하면 바로 반영됨

2. 윈도우 폴더에서 더블클릭하여 실행(크롬, 엣지, 웨일 등의 브라우저로 열기)
