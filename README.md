# Rust ChessBot 

Hand-written chess movements and rules in Rust, intended to compile to web assembly to live in the frontend on my website! 

# History 

This is the second iteration of my chessbot, with the first implementing a Chess Engine in Python & Rust, with python intended to be the GUI. However, after developing my website and seeing the results of 1.0, I thought it necessary to rewrite the chess engine for the browser!

# Play

Try your hand against my chessbot!! Visit my portfolio website: https://dannyproano.com/chess/board

# Install

Download the repo

```
cargo build && cargo run
```

To take to web assembly:

```
wasm-pack build --target web
```
