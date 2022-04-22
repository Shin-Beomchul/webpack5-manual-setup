# webpack5-manual-setup
```
모던 프레임워크는 node 모듈의 의 조합이다. 불행하게도 이 노드간 의존성은 블랙홀 보다 깊다는 우스갯 소리가 있을만큼 노드간 의존성이 강하다.
따라서 우리는 프레임워크 cli가 Schaffold 해주는 템플릿에서 버전을 업데이트 시 오류가 발생 할 경우  
꼬리에 꼬리를 블랙홀 같이 깊게 연결된 의존성에 의해 오류가 발생하는 경우가 많다.

따라서 우리는 번들러를 이해 해야 한다.
많은 번들러중 가장 기본이 되는 webpack을 가지고 가능한 모든 조합의 번들링 설정을 해보고자 한다.
```

webpack5 Manual Setup

- nvm install 16.14.2
- yarn set version berry
- yarn add -D webpack :  번들러 모듈
- yarn add -D webpack-cli : webpack 명령어를 사용할 수 있게해주는 모듈
- yarn add -D webpack-dev-server : node local server
- yarn add -D html-webpack-plugin : template html 파일에 번들 파일을 자동으로 추가해주는 플러그인
- yarn add -D @babel/core : 트랜스파일러 모듈
- yarn add -D @babel/preset-env : 트랜스파일링 기본 preset 모듈
- yarn add -D babel-loader : 트랜스파일링 하기위한 파일 loader
- touch webpack.config.js

