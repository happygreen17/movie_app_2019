#Movie App 2019

React Js Fundamentals Course(2019 Update!)


새로운 리액트 프로젝트 애플리케이션 생성하기 :
    - cmd창에서 npx create-react-app movie_app_2019 를 실행한다. -> 해당 경로에 movie_app_2019 폴더가 생성된다.

    - visual studio code에서 File - Open Folder로 해당 movie_app_2019 폴더를 연 뒤

    - package.json에서
        ,
        "test": "react-scripts test",
        "eject": "react-scripts eject" 를 삭제한다.

    - yarn.lock 파일을 삭제한다. - ( yarn은 npm과 동일한 역할을 한다. 필요없으니 삭제 )
        그러나 내 src 폴더 내에는 yarn은 없고 package-lock.json만 있었다... 찾아보니 yarn의 lock 파일이냐 npm의 lock 파일이냐의 차이인 것 같다.
        존재 이유 : 여러 사람이 협업할 때 버전에 따른 빌드 오류 최소화 https://hyunjun19.github.io/2018/03/23/package-lock-why-need/
        다른 종류의 lock 파일 : https://stackoverflow.com/questions/44552348/should-i-commit-yarn-lock-and-package-lock-json-files

    - 터미널 - new Terminal 클릭으로 아래의 터미널 창을 연 뒤 npm start 을 입력한다.

    - ctrl + c 버튼으로 종료할 수 있다.

깃허브 생성하기 :
    - 하단의 터미널 창에서 해당 movie_app_2019 에서 git init 명령어를 입력.
        Initialized empty Git repository in F:/vuejs_1/react/movie_app_2019/.git/ 가 출력됨..

    - https://github.com/new 로 이동, 
