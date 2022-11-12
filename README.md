Just a test project to work with Ethereum but using Rust.

I'm using plain Rust here, not Foundry. In future we will use Foundry.

Hope you're already following my youtube channel where I build stuff with Rust - 
https://www.youtube.com/c/AkhilSharmaTech

Quick note if you want to run this project on your system.

1. You need Rust installed
2. You need Ganache installed globally

Clone this repo, `cd` into it and then -

There are two separate files that can be compiled into different binaries, so you run either of the below commands - 

``` bash
cargo run --bin transact
cargo run --bin deploy
```
Depending on the option you pass after `--bin`, the particular binary will run.
