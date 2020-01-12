# Node.js - MySQL

생활코딩 Node.js - MySQL

## Github의 취약성 알림 대처방법

https://blog.sonim1.com/225

## npm install

    npm install

package.json의 dependencies는 우리가 사용하는 애플리케이션이 의존하고 있는 다른 라이브러리를 의미한다.

여기서는 sanitize-html 이라는 라이브러리를 현재 사용하고 있고 세팅을 해주어야한다.

여기서 사용하는 명령이 npm install 이다.

npm install을 사용하면 node.js 의 package manager가 package.json의 dependencies를 보고 sanitize-html이 필요한 것을 보고

node_modules라는 폴더에 저장해준다.

## mysql 모듈 설치

node.js가 가지고 있는 기본 모듈중에 mysql을 제어하는 모듈이 없다.

누군가가 만들거나 직접 만들어야한다.

https://www.npmjs.com/package/mysql

    npm install --save mysql
    npm install -S mysql

-S 또는 --save를 사용하면 package.json의 dependencies에 mysql 모듈을 추가해준다.
