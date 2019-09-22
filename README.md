1. You need the following dependencies installed:

```
rustup rustc cargo wasm-pack npm
```

``` 
cargo-generate(optional: used to create initial code)
```

[For rustup, rustc, cargo](https://www.rust-lang.org/tools/install)

[For wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)

[For npm](https://www.npmjs.com/get-npm)

2. In root dir, run:

```
wasm-pack build
```

This should create a "pkg" dir

3. Go to www dir, run this once

```
npm install
```

This should install your packages

4. Still in www dir, run:

```
npm run start
```

5. An navigate here to see the wasm example!

```
localhost:8080
```