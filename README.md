# stylus-media-queries

Stylus mixins to quickly write media queries for adaptative and responsive design

## Install

With [npm](http://npmjs.org) do:

```bash
$ npm install stylus-media-queries --save
```

## Usage

```css
@import "../node_modules/stylus-media-queries/index.styl";

+max-screen(800px)
    font-size: 11px;

```

## Mixins

Currently available mixins :
```css
/* Screen sizes */
screen(minWidth, maxWidth)
max-screen(maxWidth)
min-screen(minWidth)
screen-height(minHeight, maxHeight)
max-screen-height(maxHeight)
min-screen-height(minHeight)

/* Pixel density */
hdpi(density)
```

## License

MIT