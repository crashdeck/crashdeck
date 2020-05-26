# Loggie.io

Start to log everything in just few clicks

## Features

- Easy to install on your website/app
- Log with different sverity level (info, debug, warning, error, fatal)
- Differentiate logs with channels
- More coming soon

## Installing

```bash
$ npm install loggie-io
```

## Example

### Node.js

```js
const loggie = require('loggie-io');

loggie.init({
  secretKey: "<secret-key>",
  bucketId: "<bucket-id>"
})
// axios.<method> will now provide autocomplete and parameter typings
```
Start to push logs

```js
loggie.info({
  message: "This is a testing info log"
})
// axios.<method> will now provide autocomplete and parameter typings
```