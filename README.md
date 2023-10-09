# simple-login-npm-package
Publish simple login npm package

# if you need update package then you will have to do following steps;
1) change version on package.json
2) npm install
3) npm run build ( build new dist file and then you need to publish it on npm)
4) npm publish


# published package . we can install as following
 npm i package-name --save

import { LoginForm }  from 'iblox-loginform-shared-components'

 <LoginForm onSubmit={handleLogin}/>
 
