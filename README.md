# diagnose
A tool used for checking whether the client can connect to specific server's port.
It should use WebSocket, but unfortunate, now the websocket protocal doesn't support to expose the detail error of the server returns, so I use ActionScrip to solve the problem.

###Preparation
You should set flash policy file first, you can use socketpolicy.pl i provided for test:
> sudo ./socketpolicy.pl > /dev/null &

otherwise, you will get an "flash policy file" error.

###Credits
[HTML5 Web Socket implementation powered by Flash](https://github.com/gimite/web-socket-js)
