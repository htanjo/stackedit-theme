# stackedit-theme
> Custom theme extension for StackEdit

## Usage
**[StackEdit](https://stackedit.io/editor) -> Settings -> Extensions -> UserCustom extension**

Paste this code and activate "UserCustom extension".
```js
userCustom.onReady = function () {
  $('head').append('<link rel="stylesheet" href="//htanjo.github.io/stackedit-theme/stackedit-theme.css">');
};
```

## License
Copyright (c) 2015-2016 Hiroyuki Tanjo. Licensed under the [MIT License](LICENSE).
