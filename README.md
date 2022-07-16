# Jarvis

> this is a WIP, 👷👷

Jarvis is a command line tool (for current phase) which powers my daily work. Some works he can do include:

- ASR, voice command dedication, it can even add todo for automaticall;
- Scan the network, in every single PC he runs, he will sniffer the local network and gather as many useful information as possible for me;
- He can even call the camera, and detect useful information (activities) he sees;
- TTS, it can do tts inference on local in pure Rust;
- Control my IOT devices automatically in mqtt protocal.


## Install

**Jarvis** now lives in crates.io, you can install from: https://crates.io/crates/jarvis-rust via

```
cargo install jarvis-rust
```

Then you will have a `jarvis` command in cargo bin folder.

For more usage, please waiting for my updates.

## Accelerate in China

If you get a slow speed to install cargo crates, then set this in your `~/.cargo/config`:

```
[source.crates-io]
registry = "https://github.com/rust-lang/crates.io-index"


replace-with = 'tuna'

[source.tuna]
registry = "https://mirrors.tuna.tsinghua.edu.cn/git/crates.io-index.git"
```

Then `cargo install` would be faster.


## License

All rights reserved by Lucas Jin @ 2022
