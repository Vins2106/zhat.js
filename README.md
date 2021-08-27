# Zhat.js
```
Official API wrapper for https://zhat.cf
```
- [developer]()

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

# Docs
## Classes
#### Client
```
new Client()
```
- return #Client

#### BaseClient
```
none
```

### Events
#### ready
```
<client>.on("ready", () => {
  console.log("Ready!")
});
```
- return #None
#### message
```
<client>.on("message", (message) => {
  console.log(message)
});
```
- return #Message

### Methods
#### login
```
<client>.login('token')
```

