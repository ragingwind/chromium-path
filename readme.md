# chromium-path

> Getting path for chromium / chrome, it returns paths of chromium / chrome installed on your system


## Install

```
$ yarn add chromium-path

or

$ npm install chromium-path
```

# Usage

```js
const chromiumPath = require('chromium-path');

chromiumPath().then(res => console.log(res));
//=> { 'google-chrome': '/Applications/Google Chrome.app/Contents/MacOS/Google Chrome', 'google-chrome-canary': '/Applications/Google Chrome Canary.app/Contents/MacOS/Google Chrome Canary', chromium: '/Applications/Chromium.app/Contents/MacOS/Chromium' }
```

## License

MIT © [Jimmy Moon](http://ragingwind.me)
