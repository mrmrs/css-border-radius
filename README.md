# css-border-radius 1.0.6

Css module of single purpose classes for border radius

#### Stats

276 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-border-radius
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-border-radius
```

ssh:
```
git clone git@github.com:tachyons-css/css-border-radius.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-border-radius";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-border-radius@1.0.6/css/css-border-radius.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-border-radius">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   BORDER RADIUS
*/
.brn { border-radius: 0; }
.br { border-radius: .125rem; }
.br2 { border-radius: .25rem; }
.br3 { border-radius: .5rem; }
.br4 { border-radius: 1rem; }
.br5 { border-radius: 2rem; }
.br-circ { border-radius: 9999px; }
.br-100 { border-radius: 100%; }
@media screen and (min-width: 48em) {
 .brn-ns { border-radius: 0; }
 .br-ns { border-radius: .125rem; }
 .br2-ns { border-radius: .25rem; }
 .br3-ns { border-radius: .5rem; }
 .br4-ns { border-radius: 1rem; }
 .br5-ns { border-radius: 2rem; }
 .br-circ-ns { border-radius: 9999px; }
 .br-100-ns { border-radius: 100%; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .brn-m { border-radius: 0; }
 .br-m { border-radius: .125rem; }
 .br2-m { border-radius: .25rem; }
 .br3-m { border-radius: .5rem; }
 .br4-m { border-radius: 1rem; }
 .br5-m { border-radius: 2rem; }
 .br-circ-m { border-radius: 9999px; }
 .br-100-m { border-radius: 100%; }
}
@media screen and (min-width: 64em) {
 .brn-l { border-radius: 0; }
 .br-l { border-radius: .125rem; }
 .br2-l { border-radius: .25rem; }
 .br3-l { border-radius: .5rem; }
 .br4-l { border-radius: 1rem; }
 .br5-l { border-radius: 2rem; }
 .br-circ-l { border-radius: 9999px; }
 .br-100-l { border-radius: 100%; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

