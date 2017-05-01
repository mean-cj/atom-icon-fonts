# atom-icon-fonts

[![apm](https://img.shields.io/apm/l/icon-fonts.svg?style=flat-square)](https://atom.io/packages/icon-fonts)
[![apm](https://img.shields.io/apm/v/icon-fonts.svg?style=flat-square)](https://atom.io/packages/icon-fonts)
[![apm](https://img.shields.io/apm/dm/icon-fonts.svg?style=flat-square)](https://atom.io/packages/icon-fonts)
[![Travis](https://img.shields.io/travis/idleberg/atom-icon-fonts.svg?style=flat-square)](https://travis-ci.org/idleberg/atom-icon-fonts)
[![David](https://img.shields.io/david/dev/idleberg/atom-icon-fonts.svg?style=flat-square)](https://david-dm.org/idleberg/atom-icon-fonts?type=dev)

Atom snippets for Font Awesome and Bootstrap Glyphicons

the original package is also available on
[idleberg/atom-icon-fonts](https://github.com/idleberg/atom-icon-fonts)

## Installation

### apm

* Install package `apm install icon-fonts` (or use the GUI)

### Using Git

1. Change directory `cd ~/.atom/packages/`
2. Clone repository `git clone https://github.com/mean-cj/atom-icon-fonts icon-fonts`

## Usage

Snippets are limited to the `.text.html`, `source.(css|less|sass|scss|stylus)` and `.source.js.jsx` scopes. Typing the class name of an icon using the designated prefix will complete to a tag containing the icon class. Exceptions are `fa-stack` (`<span>`) and `fa-ul` (`<ul>`).

### Prefixes

Prefix         | Icon Font                           | Version
---------------|-------------------------------------|---------
`fa`           | [Font Awesome][fa]                  | 4.7.0
`glyphicon`    | [Bootstrap Glyphicons][glyphicon]   | 3.3.6

Several previously supported fonts have been removed and are now available in the [SVG icons](https://github.com/idleberg/atom-svg-icons) package or the icon fonts [legacy package](https://github.com/idleberg/atom-icon-fonts-legacy).

Examples:

* `fa-check`+<kbd>Tab</kbd> completes to `<i class="fa fa-check"></i>`
* `glyphicon-check`+<kbd>Tab</kbd> completes to `<span class="glyphicon glyphicons-check"></span>`
* well, you get the idea

### CDNs
is not support

## License

This work is licensed under the [The MIT License](LICENSE.md).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/atom-icon-fonts) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`

[ai]: http://www.androidicons.com
[brandico]: https://github.com/fontello/brandico.font
[cc]: https://github.com/cc-icons/cc-icons
[dashicons]: https://github.com/WordPress/dashicons
[devicons]: https://github.com/vorillaz/devicons
[el]: https://github.com/reduxframework/Elusive-Icons
[fa]: https://github.com/FortAwesome/Font-Awesome
[fi]: http://zurb.com/playground/foundation-icons
[fl]: https://github.com/Lukas-W/font-linux
[geomicon]: https://github.com/jxnblk/geomicons-open
[glyphicon]: https://getbootstrap.com/components/#glyphicons
[icofont]: http://icofont.com/
[icono]: https://github.com/saeedalipoor/icono
[ion]: https://github.com/driftyco/ionicons
[line]: http://www.elegantthemes.com/blog/resources/how-to-use-and-embed-an-icon-font-on-your-website
[mdi]: https://github.com/Templarian/MaterialDesign-Webfont
[mfg]: https://github.com/MfgLabs/mfglabs-iconset
[mfizz]: https://github.com/fizzed/font-mfizz
[octicon]: https://github.com/primer/octicons/tree/v4.1.0
[oi]: https://github.com/iconic/open-iconic
[openwebicons]: https://github.com/pfefferle/openwebicons
[pf]: https://github.com/vendocrat/PaymentFont
[ratchicon]: http://goratchet.com/components/#ratchicons
[st]: https://github.com/parkerbennett/stackicons
[typcn]: https://github.com/stephenhutchings/typicons.font
[ui]: http://semantic-ui.com/elements/icon.html
[wi]: https://github.com/erikflowers/weather-icons
[zmdi]: https://github.com/zavoloklom/material-design-iconic-font
