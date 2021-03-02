# NodeJs-Interview-Questions
A collection of Interview Questions


How to create a simple server in NodeJs without express.js?

By writing following line of code, you can create a server in Node Js.

```js
var http =require('http');

http.createServer(function(req,res){
  res.writeHead(200,{'Content-Type':'text/plain'});
  res.end('Hello World\n');
}).listen(1320,'127.0.0.3');
```
