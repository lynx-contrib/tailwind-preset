# @lynx-contrib/tailwind-preset

A [tailwindcss preset](https://v3.tailwindcss.com/docs/presets) for lynx, it will remove all the tailwindcss features that are not supported in lynx.

## Usage

In your `tailwind.config.js`:

```js
import preset from "@lynx-contrib/tailwind-preset";

export default {
  presets: [
    preset,
  ],
};

```
