</p>
<a href="https://github.com/fuwn/lime">
<h1 align="center">🧶 lime</h1>
</a>
<p align="center">
no bs url shortening
</p>

<p align="center">
<a href="https://discord.com/invite/yWKgRT6">
<img src="https://img.shields.io/discord/246524734718738442" alt="discord" />
</a>
<a href="https://www.codefactor.io/repository/github/fuwn/lime">
<img src="https://www.codefactor.io/repository/github/fuwn/lime/badge" alt="codefactor" />
</a>
<a href="https://saythanks.io/to/fuwnzy@gmail.com">
<img src="https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg" alt="say thanks" />
</a>
<a href="./LICENSE">
<img src="https://img.shields.io/github/license/fuwn/lime" alt="license" />
</a>
</p>

## nix
- build: `nix-build`
- docker: `nix-build docker.nix`

## usage (without docker)
- run (dev): `cargo run`

## contributing
please reference the [contribution guidelines](./contributing.md) of this repository.

## development dependencies
### required
- [diesel_cli](https://crates.io/crates/diesel_cli)
- [cargo-make](https://github.com/sagiegurari/cargo-make)

### optional
- [cargo-watch](https://crates.io/crates/cargo-watch)

*these development dependencies will automatically be satisfied if you are using the nix
shell configuration as provided.*

### license
[gnu general public license v3.0](./license)
