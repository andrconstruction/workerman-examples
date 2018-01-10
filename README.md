Examples for simple websocket server on php https://github.com/walkor/Workerman.

Examples directory:
* integration - single daemon (tcp-server + ws-server) + script that can send personal message by clientId, userId, cookie
* integration2 - 1 tcp-server + 4 ws-workers + script that can send personal message by clientId, userId, cookie

Run from console:
* start: "php server.php start" or "php server.php start -d"
* stop: "php server.php stop"
* restart: "php restart.php restart"
* reload: "php reload.php reload"

###License

(The MIT License)

Copyright (c) 2017 Vladimir Goncharov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
