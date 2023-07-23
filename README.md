# Created a server , run it on port 4000 and console my name.

var http = require('http')
http.createServer(function(req, res){
    res.end("Manasi Gautam")
}).listen(4000)
