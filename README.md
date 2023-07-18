# MQTT Pub/Sub Example App

A simple Rust-based app that creates an MQTT subscriber and publisher

## Usage

1. Compile with `cargo build`
1. Start subscriber `./target/debug/sub`
1. Start publisher `./target/debug/pub`

| Publisher | Subscriber
|---|---
| Publishing messages on topic "rust/mqtt"<br>Publishing messages on topic "rust/test"<br>Publishing messages on topic "rust/mqtt"<br>Publishing messages on topic "rust/test"<br>Publishing messages on topic "rust/mqtt"<br>Disconnecting from the broker | Processing requests...<br>rust/mqtt: Hello world! 0<br>rust/test: Hello world! 1<br>rust/mqtt: Hello world! 2<br>rust/test: Hello world! 3<br>rust/mqtt: Hello world! 4

Press `ctrl c` to terminate the subscriber
