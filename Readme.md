## Installation

```
npm install node-server
```
## Usage
```js
const nodeserver = require("http-node-server");
const app = nodeserver()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

