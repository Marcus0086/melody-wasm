<div align="center">

  <h1><code>Melody-Wasm-Port</code></h1>

  <strong>A compiler in wasm for web apps using <a href="https://github.com/yoav-lavi/melody">Meldoy</a>.</strong>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The Rust and WebAssembly Working Group</a></sub>
</div>

## About

This is just a port of melody compiler by <a href="https://github.com/yoav-lavi">yoav-lavi</a>
into web assembly using wasm-bindgen

Be sure to check out [other `wasm-pack` tutorials online][tutorials] for other
templates and usages of `wasm-pack`.

[tutorials]: https://rustwasm.github.io/docs/wasm-pack/tutorials/index.html
[template-docs]: https://rustwasm.github.io/docs/wasm-pack/tutorials/npm-browser-packages/index.html


## Usage

Just clone this package and include it in your project

* Be Sure to add required config for your bundler (webpack) by turning the asyncwebassembly to `true`.
* Now add the package to your package.json
```js
  "dependencies": {
    "regex-wasm": "file:./pkg"
  },
```
* Now simply import it like some another package
```js
  import * as wasm from 'regex-wasm'
```