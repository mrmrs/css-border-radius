# CSS BORDER RADIUS

  Mobile-first classes for css-border-radius.
  Set the desired css-border-radius on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-border-radius
```
or download the css on github and include in your project.

## File Size


## The Code
```
  .brn {     border-radius: 0; }
  .br {      border-radius: .125rem; }
  .br2 {     border-radius: .25rem; }
  .br3 {     border-radius: .5rem; }
  .br4 {     border-radius: 1rem; }
  .br5 {     border-radius: 2rem; }
  .br-circ { border-radius: 9999px; }
  .br-100 {  border-radius: 100%; }

@include break(not-small) {
  .brn-ns {     border-radius: 0; }
  .br-ns {      border-radius: .125rem; }
  .br2-ns {     border-radius: .25rem; }
  .br3-ns {     border-radius: .5rem; }
  .br4-ns {     border-radius: 1rem; }
  .br5-ns {     border-radius: 2rem; }
  .br-circ-ns { border-radius: 9999px; }
  .br-100-ns {  border-radius: 100%; }
}

@include break(medium) {
  .brn-m {     border-radius: 0; }
  .br-m {      border-radius: .125rem; }
  .br2-m {     border-radius: .25rem; }
  .br3-m {     border-radius: .5rem; }
  .br4-m {     border-radius: 1rem; }
  .br5-m {     border-radius: 2rem; }
  .br-circ-m { border-radius: 9999px; }
  .br-100-m {  border-radius: 100%; }
}

@include break(large) {
  .brn-l {     border-radius: 0; }
  .br-l {      border-radius: .125rem; }
  .br2-l {     border-radius: .25rem; }
  .br3-l {     border-radius: .5rem; }
  .br4-l {     border-radius: 1rem; }
  .br5-l {     border-radius: 2rem; }
  .br-circ-l { border-radius: 9999px; }
  .br-100-l {  border-radius: 100%; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

