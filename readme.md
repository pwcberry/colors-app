# colors-app

> Copy color values from popular palettes. Supports HEX, RGB, and HSL formats.

##### Current Palettes
- [Material Design](https://material.io/guidelines/style/color.html)
- [Open Color](https://yeun.github.io/open-color/)
- Please suggest more!

##### Why?

One night I asked myself, "Self, what can I build in **two hours** using [Preact](https://github.com/developit/preact)?" :thinking: <br>
The [initial version](https://github.com/lukeed/colors-app/tree/433ab81727b136da7bd7f8d3f5ca9c9a42ad3d15) took _less than 2 hours_ and [I was pretty happy](https://twitter.com/lukeed05/status/812088705171107840) with it.<sup>*</sup> :smile:

Additional features (and other changes) have and will continue to improve this web app.

> **<sup>*</sup>** I got a head start by using [`fly-kit-preact`](https://github.com/lukeed/fly-kit-preact). Webpack users may want to see [`preact-starter`](https://github.com/lukeed/preact-starter) instead!

## Install

```sh
git clone https://github.com/lukeed/colors-app
npm install
npm start
```

> :exclamation: **Pro Tip:** Use [Yarn](https://yarnpkg.com/) to install dependencies 3x faster than NPM!

## Development

### Commands

Any of the following commands can (and should :wink:) be run from the command line.

> If using [Yarn](https://yarnpkg.com/), all instances of `npm` can be replaced with `yarn`. :ok_hand:

#### build

```
$ npm run build
```

Compiles all files. Output is sent to the `dist` directory.

#### start

```
$ npm start
```

Executes [`build`](#build) and runs your application (from the `dist` directory) in the browser.

#### watch

```
$ npm run watch
```

Like [`start`](#start), but will auto-compile & auto-reload the server after any file changes within the `src` directory.


## License

MIT © [Luke Edwards](https://lukeed.com)
