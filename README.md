
# jquery-animate-gradient

 [![Patreon](https://img.shields.io/badge/Support%20me%20on-Patreon-%23e6461a.svg)][patreon] [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/jquery-animate-gradient.svg)](https://www.npmjs.com/package/jquery-animate-gradient) [![Downloads](https://img.shields.io/npm/dt/jquery-animate-gradient.svg)](https://www.npmjs.com/package/jquery-animate-gradient) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> Animate gradient colors.

## :cloud: Installation

```sh
$ npm i --save jquery-animate-gradient
```


## :memo: Documentation


### `animateGradient(jQueryElement, top, bottom, {}, {}, callback)`
Animates a gradient.

**Usage:**

```js
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], 2000, 100, function () {});
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], 2000, function () {});
$.animateGradient(".jQuerySelector", [0, 0, 0], [0, 0, 0], function () {});
```

#### Params
- **jQuery|String** `jQueryElement`: The jQuery element or selector.
- **Array** `top`: An array of values interpreted by `rgb()` and representing the top color.
- **Array** `bottom`: An array of values interpreted by `rgb()` and representing the bottom color.
- **** `{}`: duration The duration of animation in miliseconds (default: `1000`).
- **** `{}`: delay Delay of interval (default: `100`).
- **Function** `callback`: The callback function.



## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :moneybag: Donations

Another way to support the development of my open-source modules is
to [set up a recurring donation, via Patreon][patreon]. :rocket:

[PayPal donations][paypal-donations] are appreciated too! Each dollar helps.

Thanks! :heart:


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[patreon]: https://www.patreon.com/ionicabizau
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
