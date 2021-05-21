# NODE MODULE

Fetches mentioned User's repository information using axios.

## Current project usage:
To fetch all repositories with extra details of the mentioned github user

User can be changed by setting username in index.js file

# STEPS

- Initial Setup: Create an npm package/folder in local directory

```
mkdir <folder-name> && cd <folder-name>
mkdir node-module-1 && cd node-module-1

npm init
or
npm init -y

(...install any required modules)
```

- Code Setup: Write your desired code in index.js
  example:

```
module.exports = function (msg) {
    console.log(msg);
};
```

- Execute the code OR Test in a different project using require function

```
node index.js

const greet = require("node-module-1")
```

- Publish the code(sign up on https://www.npmjs.com/)

```
npm login

npm publish
```

- To Re publish the module

```
//firstly change the version number in package.json file (e.g. 1.0.0 > 1.0.1)

npm publish
```

You check your packages by searching on https://www.npmjs.com/
