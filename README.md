# echo-server
A simple TCP echo server. This server is based on the [tokio](https://github.com/tokio-rs/tokio) I/O support crate, and was derived from the example code [here](https://tokio.rs/docs/getting-started/simple-server/).

## Usage
Start the server with `echo-server`.
Test the server using `telnet localhost 12345`. The server should echo your messages on this telnet session.
