# Nacelle

Sora Sagano's excellent [Nacelle](https://dotcolon.net/font/nacelle/).


## Usage

```html
<link rel="stylesheet" href="nacelle.css" type="text/css" charset="utf-8" integrity="sha384-6yK29EJyAhGXCLAXNG26WGjvPlnorYepCLOp03oQD6GiSmi+CZhwXnG13bJpctAm" crossorigin="anonymous" />
<style>
  body {
    font-family: "Nacelle";
    font-weight: 400;
  }
</style>
```

Note: if you modify the css file, use the following to re-compute the css resource integrity hash

    $ cat nacelle.css | openssl dgst -sha384 -binary | openssl base64 -A
    6yK29EJyAhGXCLAXNG26WGjvPlnorYepCLOp03oQD6GiSmi+CZhwXnG13bJpctAm
