# connect-fonts-vt323

VT323 fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-vt323");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/vt323-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* vt323-regular

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/vt323-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin
* en

5. Set your CSS up to use the new font by using the "VT323" font-family.
```
    body {
      font-family: 'VT323', 'sans-serif', 'serif';
    }
```

## Font Info
VT323

* Copyright: Copyright (c) 2011, Peter Hull (peter.hull@oikoi.com), with Reserved Font Name "VT323".

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-vt323
* Repo: https://github.com/shane-tomlinson/connect-fonts-vt323

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

