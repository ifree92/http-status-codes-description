# HTTP Status codes description

Module is the DB with information about all available http status codes.

Usage example:

```js
var httpStatusCodes = require("http-status-codes-description");
console.log(httpStatusCodes(201));
```

Output example:

```js
{
	type: 'Informational',
	desc: 'Created'
}
```