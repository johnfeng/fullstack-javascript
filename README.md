# fullstack-javascript

## Dev IDE

Atom: https://atom.io/

## Example 101

## server-1.js
```
var express = require('express'),
     http = require('http');

var hostname = 'localhost';
var port = 3000;

var app = express();

app.use(function (req, res, next) {
  console.log(req.headers);
    res.writeHead(200, { 'Content-Type': 'text/html' });
  res.end('<html><body><h1>Hello World</h1></body></html>');

});

var server = http.createServer(app);

server.listen(port, hostname, function(){
  console.log(`Server running at http://${hostname}:${port}/`);
});
```

`npm install express --save`

`node server-1`

`npm install morgan --save`

## Project template

https://github.com/bhajian/express-togo

## Other related projects

http://www.dustjs.com/

# Attribute: 

The source code is gathered around the Internet. Please contact me if you are the author.
