# Websocket client WSCLIENT.HTML

This client create websocket listener with name `socket` with all event  methods during start html page:

- socket.onopen
- socket.onclose
- socket.onmessage
- socket.onerror

where `socket` supports all actions:

- socket.close()
- socket.send(message)

`Html page` has interactive boxes and buttons to support:

- text boox to point WS server ( by default it is: wss://echo.websocket.org );
- text box to enter message which you wish to send to WS server;
- button `Send` - to send message from text box to WS and get response.
- button `Disconnect` to stop connection to WS server.
- button `Reconnect` to start connection to WS server again after stop.

Code is in project on GitHub:

You can simply clone project from GitHub and use file `wsclient.html` for your web socket servers.

![alt text](image.png)