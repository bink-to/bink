<p align="center">
  <a href="https://cdn.itwcreativeworks.com/assets/bink/images/logo/bink-brandmark-black-x.svg">
    <img src="https://cdn.itwcreativeworks.com/assets/bink/images/logo/bink-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/bink-to/bink-to.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/bink-to.svg">
  <img src="https://img.shields.io/bundlephobia/min/bink-to.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/bink-to/bink-to.svg">
  <img src="https://img.shields.io/npm/dm/bink-to.svg">
  <img src="https://img.shields.io/node/v/bink-to.svg">
  <img src="https://img.shields.io/website/https/bink-to.to.svg">
  <img src="https://img.shields.io/github/license/bink-to/bink-to.svg">
  <img src="https://img.shields.io/github/contributors/bink-to/bink-to.svg">
  <img src="https://img.shields.io/github/last-commit/bink-to/bink-to.svg">
  <br>
  <br>
  <a href="https://bink.to">Site</a> | <a href="https://www.npmjs.com/package/bink">NPM Module</a> | <a href="https://github.com/bink/bink">GitHub Repo</a>
  <br>
  <br>
  <strong>bink</strong> is the official npm module of <a href="https://bink.to">Bink</a>, a free app for creating a link in bio page that turns your followers into customers!
</p>

## Bink Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## Features
* Getting proxy lists

### Getting an API key
You can use so much of `bink` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Bink account](https://bink.to/authentication/signup).

## Install Bink
### Install via npm
Install with npm if you plan to use `bink` in a Node project or in the browser.
```shell
npm install bink
```
If you plan to use `bink` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const bink = new (require('bink'))({
  // Not required, but having one removes limits (get your key at https://bink.to).
  apiKey: 'api_test_key'
});
```

### Install via CDN
Install with CDN if you plan to use Bink only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/bink@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var bink = new Bink({
    // Not required, but having one removes limits (get your key at https://bink.to).
    apiKey: 'api_test_Key'
  });
</script>
```

### Use without installation
You can use `bink` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## Using Bink
After you have followed the install step, you can start using `bink` to create a link in bio page that turns your followers into customers!

For a more in-depth documentation of this library and the Bink service, please visit the official Bink website.

## Use without installation
### Use Bink with `curl`
```shell
# Standard
curl -X POST https://api.bink.to
```

## What Can Bink do?
A free app that helps you [create a link in bio page](https://bink.to) that turns your followers into customers!

## Final Words
If you are still having difficulty, we would love for you to post
a question to [the Bink issues page](https://github.com/bink/bink/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
