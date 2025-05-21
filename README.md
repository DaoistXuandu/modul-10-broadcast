# Reflections

## 2.1. Original code of broadcast chat

### Server
![Gambar 1](./static/server.png)

### Client
![Gambar 2](./static/client-1.png)
![Gambar 3](./static/client-2.png)
![Gambar 4](./static/client-3.png)

To run for the server we type
```
cargo run --bin server
```
and for the client 
```
cargo run --bin client
```

Also because of this implementation is about websocket communication between client and server. So everytime client send any data to the server, the server will receive it and give back to any client it's currently connected to.
