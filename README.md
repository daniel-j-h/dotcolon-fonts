# dotcolon-fonts

Sora Sagano's excellent fonts packaged up for the web.


## Overview

- [Aileron](./aileron/README.md)
- [Nacelle](./nacelle/README.md)
- Melete
- F1.8
- F5.6
- Route 159
- Eunomia
- Penna
- Seshat
- Ferrum
- Medio
- Tenderness

The original OpenType files can be downloaded from https://dotcolon.net


## Usage

To use a font
- use the corresponding `*.css` file
- ship the `*.woff` and `*.woff2` files

Example
- use the `nacelle/v1.00/nacelle.css` file which defined the css `@font-face` mappings
- ship all `nacelle/v1.00/nacelle-*.woff` and `nacelle/v1.00/nacelle-*.woff2` files

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Nacelle</title>
    <meta name="viewport" content="initial-scale=1,maximum-scale=1,user-scalable=no">
    <link rel="stylesheet" href="nacelle.css" type="text/css" charset="utf-8" integrity="sha384-6yK29EJyAhGXCLAXNG26WGjvPlnorYepCLOp03oQD6GiSmi+CZhwXnG13bJpctAm" crossorigin="anonymous" />
    <style>
      body {
        font-family: "Nacelle";
        font-weight: 400;
      }
    </style>
  </head>
  <body>
    <h1>Nacelle</h1>
  </body>
</html>
```

If you only need specific fonts (e.g. Nacelle Regular) you can trim the `nacelle.css` and only ship e.g. `nacelle-regular.woff2` and `nacelle-regular.woff`.

Note: if you modify the css file, use the following to re-compute the css resource integrity hash

    $ cat nacelle.css | openssl dgst -sha384 -binary | openssl base64 -A
    6yK29EJyAhGXCLAXNG26WGjvPlnorYepCLOp03oQD6GiSmi+CZhwXnG13bJpctAm


## License

The web fonts are derived work from the original OpenType files and are licensed accordingly.
