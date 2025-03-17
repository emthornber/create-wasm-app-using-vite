<div align="center">

  <h1><code>create-wasm-app</code></h1>

  <strong>An <code>npm init</code> template for kick starting a project that uses NPM packages containing Rust-generated WebAssembly and bundles them using Vite.</strong>

  <p>
    <a href="https://travis-ci.org/emthornber/create-wasm-app-using-vite"><img src="https://img.shields.io/travis/emthornber/create-wasm-app-using-vite.svg?style=flat-square" alt="Build Status" /></a>
  </p>

  <h3>
    <a href="#usage">Usage</a>
    <span> | </span>
    <a href="https://discordapp.com/channels/442252698964721669/443151097398296587">Chat</a>
  </h3>

  <sub>Built with 🦀🕸 by <a href="https://emthornber.github.io/">Mark Thornber using a fork from the Rust and WebAssembly Working Group</a></sub>
</div>

## About

This template is designed for depending on NPM packages that contain
Rust-generated WebAssembly and using them to create a Website.

* Want to create an NPM package with Rust and WebAssembly? [Check out
  `wasm-pack-template`.](https://github.com/rustwasm/wasm-pack-template)
* Want to make a monorepo-style Website without publishing to NPM? Check out
  [`rust-webpack-template`](https://github.com/rustwasm/rust-webpack-template)
  and/or
  [`rust-parcel-template`](https://github.com/rustwasm/rust-parcel-template).

## 🚴 Usage

```
npm init wasm-app-using-vite
```

## 🔋 Batteries Included

* `.gitignore`: ignores `node_modules`
* `LICENSE-APACHE` and `LICENSE-MIT`: most Rust projects are licensed this way, so these are included for you
* `README.md`: the file you are reading now!
* `index.html`: a bare bones html document that includes the vite bundle
* `index.js`: example js file with a comment showing how to import and use a wasm pkg
* `package.json` and `package-lock.json`:
  * pulls in devDependencies for using vite:
    * [`vite`](https://www.npmjs.com/package/vite)
    * [`vite-plugin-top-level-await`](https://www.npmjs.com/package/vite-plugin-top-level-await)
    * [`vite-plugin-wasm`](https://www.npmjs.com/package/vite-plugin-wasm)
  * defines a `start` script to run `vite preview`
* `vite.config.js`: configuration file for bundling your js with webpack

## License

Licensed under either of

* Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
