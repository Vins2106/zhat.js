# NOTE: FOR NOW, THIS PACKAGE NOT USEABLE.
# Zhat.js
```
Official API wrapper for https://zhat.cf
```

# Install to use
```
npm i zhat.js
```

# Example
```
const Zhat = require("zhat.cf");
const client = new Zhat.Client();

client.on("ready", () => {
  console.log(`Login as ${client.user.username}`)
});

client.login('token');
```