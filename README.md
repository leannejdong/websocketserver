# websocketserver

We exercise to build a basic message relay service connects clients voa websockets.

* What are TCP, HTTP

* TCP connections on socket

* Parse a small number of HTTP requests

* Create a proper HTTP response

* Improve the throughout of our server with a thread pool

## Dependency

* run web server->`warp` and `tokio`

* serialize, deserialize JSON-> `Serde

* create connection ID-> `uuid`

* async data streams of websocket -> `futures`


I yet to implement the above approach, which will be much faster than the current trait approach ;) Later~