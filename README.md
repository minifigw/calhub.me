# calhub.me
CLUBHUB redirect
var http = require('follow-redirects').http;https://mailchi.mp/666130923bee/clubhub
var https = require('follow-redirects').https;https://mailchi.mp/666130923bee/clubhub

http.get('http://bit.ly/900913', function (response) {
  response.on('data', function (chunk) {
    console.log(chunk);
  });
}).on('error', function (err) {
  console.error(err);
});
