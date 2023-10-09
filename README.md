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

function App() {

  const handleLogin = (formData) => {
    // Handle login logic for App1
    console.log('App1 logged in with:', formData);
  };

  return (
    <div className="App">
       <h1>App 1 Login Page</h1>
       <LoginForm onSubmit={handleLogin}/>
    </div>
  );
}

export default App;
 
