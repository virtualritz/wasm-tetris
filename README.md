# Wasm Tetris

A Rust/WebAssembly 'learning by doing' example.

![Snapshot](/snapshot.png)

## Development setup

Install Rust compiler target `wasm32-unknown-unknown`:

```
$ rustup target add wasm32-unknown-unknown
```

Install JS dependencies:

```
$ npm install
```

Build:

```
$ ./build.sh
```

Start webpack dev server:

```
npm run dev
```

## References

- https://en.wikipedia.org/wiki/Tetris
- https://github.com/rustwasm/wasm-bindgen
- https://developer.mozilla.org/en-US/docs/WebAssembly

## License

[MIT](http://opensource.org/licenses/MIT)
