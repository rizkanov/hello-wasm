# Rust Project hello-wasm
This project was created to compile a Rust project and display the resulting WebAssembly (WASM) on a web page.

Clone project

## Generate Rust to Web

```bash
wasm-pack build --target web
```

## Make package available to npm

```bash
wasm-pack build --target bundler
```
