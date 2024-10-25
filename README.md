## Prepare

Install compilation dependencies

```shell
sudo apt-get install -y lld
```

<br/>

## Build

**Build move-language**

```shell
cargo build
```

**Install move-cli**

By default, it installs the executable files into the `bin` folder in the `CARGO_HOME` directory (usually `~/.cargo/bin`)

```shell
cargo install --path language/tools/move-cli
```

**Verify installation**

```shell
move -h
```

<br/>

## Note:
This was the home of the Move language from inception to ~2022. This repository is no longer maintained, but development continues in https://github.com/move-language/move-on-aptos and https://github.com/move-language/move-sui.
