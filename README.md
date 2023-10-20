# STARKLINGS
fork from: https://github.com/shramee/starklings-cairo1

### My journey in learning Cairo with Starklings :)

![image](https://github.com/iBeccoo/starklings-cairo1/assets/101125593/75ba0fd4-d4fa-434b-ad03-628f77cd88f0)

---

## Setup and run

Make sure you have Rust and Cargo installed with the `default` toolchain.  
With rustup `curl https://sh.rustup.rs -sSf | sh -s`

1. Clone the repo and go in the directory,  
   `git clone https://github.com/shramee/starklings-cairo1.git && cd starklings-cairo1`.
2. Run `cargo run -r --bin starklings`, this might take a while the first time.
3. You should see this intro message, run `cargo run -r --bin starklings watch` when you are ready!

## Start at a specific exercise `NEW`

To start watch at a specific exercise pass the name of the exercise to watch command.
For example, to start at `starknet1`,

```
cargo run -r --bin starklings watch starknet1
```
