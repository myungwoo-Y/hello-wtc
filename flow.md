# Github flow

Vincent Driessen이 말한 branching model를 구현한 Git 확장 모듈이다.

기본 브런치는 5가지를 이야기한다. feature > develop > release > hotfix > master 브런치가 존재하며, 머지 순서는 앞에서 뒤로 진행된다. release 브런치와 hotfix 브런치의 경우, develop 브런치의 오른쪽에 존재하기에 모두 develop 브런치도 머지를 하도록 구성이 되어있다.

Vincent Driessen은 관련하여 스크립트로 명령을 구성해놨으며, 그냥 설치를 하여 CLI에서 명령으로 작업을 하여도 되고, GUI 툴들에서 기본 내장 git-flow 명령이나 플러그인을 설치하여 작업을 진행할 수 있도록 보편화되어있는 브런칭 모델이다.

![Github Flow](http://nvie.com/img/git-model@2x.png)

