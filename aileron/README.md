# Aileron

Sora Sagano's excellent [Aileron](https://dotcolon.net/font/aileron/).


## Usage

```html
<link rel="stylesheet" href="aileron.css" type="text/css" charset="utf-8" integrity="sha384-M6fymAcQ+9Jx9obdEsTlFesZB1mGSpMhlwVdlOmz8VnRTpG/8cC7iZF0rzm28HAA" crossorigin="anonymous" />
<style>
  body {
    font-family: "aileron";
    font-weight: 400;
  }
</style>
```

Note: if you modify the css file, use the following to re-compute the css resource integrity hash

    $ cat aileron.css | openssl dgst -sha384 -binary | openssl base64 -A
    M6fymAcQ+9Jx9obdEsTlFesZB1mGSpMhlwVdlOmz8VnRTpG/8cC7iZF0rzm28HAA
