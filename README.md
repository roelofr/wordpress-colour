# Colours for WordPress

This package provides a bunch of variables for Sass, scss and Less to be used
in conjunction with WordPress.

The colours have been obtained from the official [make.wordpress.org][1]
website.

[1]: https://make.wordpress.org/design/handbook/design-guide/foundations/colors

## What's Included

### Blue shades

- WordPress Blue (rgb(0,115,170), `#0073aa`)
- Medium Blue (rgb(0,160,210), `#00a0d2`)

## Grey

- Ultra Dark Grey (rgb(25,30,35), `#191e23`)
- Dark Grey (rgb(35,40,45), `#23282d`)
- Base Grey (rgb(50,55,60), `#32373c`)
- Dark Silver Grey (rgb(130,135,140), `#82878c`)
- Silver Grey (rgb(160,165,170), `#a0a5aa`)
- Light Silver Grey (rgb(180,185,190), `#b4b9be`)

## Accents


- Accent Red (rgb(220,50,50), `#dc3232`)
- Accent Orange (rgb(245,110,40), `#f56e28`)
- Accent Yellow (rgb(255,185,0), `#ffb900`)
- Accent Green (rgb(70,180,80), `#46B450`)
- Accent Purple (rgb(130,110,180), `#826eb4`)

## How to use

Import it into your code (the below examples assume Webpack, but you're free
to use whatever you'd like).

```less
@import (reference) '~roelofr/wordpress-colour/colour';
```

```sass
@import '~roelofr/wordpress-colour/colour'
```
