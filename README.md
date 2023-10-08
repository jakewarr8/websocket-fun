# websocket-fun

``` js
let socket = new WebSocket("ws://localhost:8080/ws")

socket.onmessage = (event) => {console.log("recvied from the server: ", event.data) }

socket.send("hello from client")

```