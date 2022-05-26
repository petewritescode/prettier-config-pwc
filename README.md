# prettier-config-pwc

My personal [Prettier](https://prettier.io/) config.

---

## Installation

This module should be installed as one of your project's `devDependencies`:

```bash
npm install --save-dev prettier-config-pwc
```

It has a `peerDependencies` entry for Prettier.

## Usage

Just add the config to your `package.json` and Prettier will automatically use it:

```json
{
  "prettier": "prettier-config-pwc"
}
```

If you'd rather keep your config outside `package.json` you can follow one of the official [alternative methods](https://prettier.io/docs/en/configuration.html#sharing-configurations) for using shareable configs. This can be useful if you want to override any settings.
