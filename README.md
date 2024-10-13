# node-input
package for creating input in CLI

# How to Use
> install and use
```bash
npm i @cryptzx-dev/node-input
```

```JavaScript
const { input } = require("@cryptzx-dev/node-input");

async(() => {
  const inputData = await input("What's ur Name")
  console.log("Your name: " + inputData)
})
```
