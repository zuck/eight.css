![eight.css](https://raw.githubusercontent.com/zuck/eight.css/master/docs/art/logo.png "eight.css")

# eight.css

> A micro (and modular) CSS framework based on 8pt grid

[Try it!](https://zuck.github.io/eight.css/)

## Usage

**Eight.css** is a modular CSS framework, so you can use it as a single bundle
or importing only the modules you need.

All **eight.css**'s CSS files are minimized but source maps are provided for each one
of them.

### As a single bundle

You can simply link to the main CSS file in your HTML page:

```html
<link rel="stylesheet" href="eight.css">
```

### As separated modules

You can import each **eight.css**'s module as a separated CSS file.

**IMPORTANT:** please, note that by default **eight.css** uses **Normalize.css**.
When you import separated modules, instead, it is **not**. This means you have
to add it manually *BEFORE* importing **eight.css** modules.

```html
<link rel="stylesheet" href="normalize.css"> /* Not included by default */
<link rel="stylesheet" href="eight.grid.css">
<link rel="stylesheet" href="eight.typography.css">
<link rel="stylesheet" href="eight.elements.css">
```

### As a package

You can also install **eight.css** using **npm**:

```bash
$ npm install eight.css
```

## Compile CSS from scratch

You can (re)compile CSS from **Stylus** source files:

```bash
git clone git@github.com:zuck/eight.css.git
cd eight.css
npm install
npm run build
```

All (minimized) CSS files and source maps will be compiled in `dist/`.

## Reference

* https://builttoadapt.io/intro-to-the-8-point-grid-system-d2573cde8632
* https://material.io/guidelines/layout/metrics-keylines.html
* https://spec.fm/specifics/8-pt-grid

## License

The MIT License (MIT)

[Read more...](./LICENSE)

Copyright (c) 2017 Emanuele Bertoldi
