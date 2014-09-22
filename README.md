# CSS OUTLINES

  Mobile-first classes for css-outlines.
  Set the desired css-outlines on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-outlines
```
View on [npm](https://www.npmjs.org/package/css-outlines)


## File Size

6.9K outlines.css
6.9K outlines.scss

## The Code
```
.oo--blk {      outline-color: $near-black; }
.oo--dk-gry {   outline-color: $dark-gray; }
.oo--md-gry {   outline-color: $mid-gray; }
.oo--gray {     outline-color: $gray; }
.oo--silver  {  outline-color: $silver; }
.oo--lt-slvr {  outline-color: $light-silver; }
.oo--lt-gry {   outline-color: $light-gray; }
.oo--near-wht { outline-color: $near-white; }
.oo--wht {      outline-color: $white; }


/* Outline Styles */

.os-none {      outline-style: none; }
.os-dots {      outline-style: dotted; }
.os-dash {      outline-style: dashed; }
.os-solid {     outline-style: solid; }
.os-double {    outline-style: double; }
.os-groove {    outline-style: groove; }
.os-ridge {     outline-style: ridge; }
.os-inset {     outline-style: inset; }
.os-outset {    outline-style: outset; }
.os-inherit {   outline-style: inherit; }


/* Outline Widths */

.ow-thin {      outline-width: thin; }
.ow-med {       outline-width: medium; }
.ow-thick {     outline-width: thick; }
.ow-3 {         outline-width: 1px; }
.ow-2 {         outline-width: 2px; }
.ow-3 {         outline-width: 3px; }
.ow-4 {         outline-width: 4px; }
.ow-5 {         outline-width: 5px; }
.ow-6 {         outline-width: 6px; }
.ow-7 {         outline-width: 7px; }
.ow-8 {         outline-width: 8px; }
.ow-9 {         outline-width: 9px; }
.ow-10 {        outline-width: 10px; }
.ow-i {         outline-width: inherit; }

.oo-1 {         outline-offset: 1px; }
.oo-2 {         outline-offset: .25rem; }
.oo-3 {         outline-offset: .5rem; }
.oo-4 {         outline-offset: 1rem; }
.oo-5 {         outline-offset: 2rem; }
.oo-i {         outline-offset: inherit; }

@media screen and (min-width: 48em) {
  .oo--blk-ns {      outline-color: $near-black; }
  .oo--dk-gry-ns {   outline-color: $dark-gray; }
  .oo--md-gry-ns {   outline-color: $mid-gray; }
  .oo--gray-ns {     outline-color: $gray; }
  .oo--silver -ns {  outline-color: $silver; }
  .oo--lt-slvr-ns {  outline-color: $light-silver; }
  .oo--lt-gry-ns {   outline-color: $light-gray; }
  .oo--near-wht-ns { outline-color: $near-white; }
  .oo--wht-ns {      outline-color: $white; }
  .os-none-ns {      outline-style: none; }
  .os-dots-ns {      outline-style: dotted; }
  .os-dash-ns {      outline-style: dashed; }
  .os-solid-ns {     outline-style: solid; }
  .os-double-ns {    outline-style: double; }
  .os-groove-ns {    outline-style: groove; }
  .os-ridge-ns {     outline-style: ridge; }
  .os-inset-ns {     outline-style: inset; }
  .os-outset-ns {    outline-style: outset; }
  .os-inherit-ns {   outline-style: inherit; }
  .ow-thin-ns {      outline-width: thin; }
@media screen and (min-width: 48em) and (max-width: 64em) {
  .ow-thick-ns {     outline-width: thick; }
  .ow-1-ns {         outline-width: 1px; }
  .ow-2-ns {         outline-width: 2px; }
  .ow-3-ns {         outline-width: 3px; }
  .ow-4-ns {         outline-width: 4px; }
  .ow-5-ns {         outline-width: 5px; }
  .ow-6-ns {         outline-width: 6px; }
  .ow-7-ns {         outline-width: 7px; }
  .ow-8-ns {         outline-width: 8px; }
  .ow-9-ns {         outline-width: 9px; }
  .ow-10-ns {        outline-width: 10px; }
  .ow-i-ns {         outline-width: inherit; }
  .oo-1-ns {         outline-offset: 1px; }
  .oo-2-ns {         outline-offset: .25rem; }
  .oo-3-ns {         outline-offset: .5rem; }
  .oo-4-ns {         outline-offset: 1rem; }
  .oo-5-ns {         outline-offset: 2rem; }
  .oo-i-ns {         outline-offset: inherit; }
}

@include break(medium) {
  .oo--blk-m {      outline-color: $near-black; }
  .oo--dk-gry-m {   outline-color: $dark-gray; }
  .oo--md-gry-m {   outline-color: $mid-gray; }
  .oo--gray-m {     outline-color: $gray; }
  .oo--silver -m {  outline-color: $silver; }
  .oo--lt-slvr-m {  outline-color: $light-silver; }
  .oo--lt-gry-m {   outline-color: $light-gray; }
  .oo--near-wht-m { outline-color: $near-white; }
  .oo--wht-m {      outline-color: $white; }
  .os-none-m {      outline-style: none; }
  .os-dots-m {      outline-style: dotted; }
  .os-dash-m {      outline-style: dashed; }
  .os-solid-m {     outline-style: solid; }
  .os-double-m {    outline-style: double; }
  .os-groove-m {    outline-style: groove; }
  .os-ridge-m {     outline-style: ridge; }
  .os-inset-m {     outline-style: inset; }
  .os-outset-m {    outline-style: outset; }
  .os-inherit-m {   outline-style: inherit; }
  .ow-thin-m {      outline-width: thin; }
  .ow-med-m {       outline-width: medium; }
  .ow-thick-m {     outline-width: thick; }
  .ow-1-m {         outline-width: 1px; }
  .ow-2-m {         outline-width: 2px; }
  .ow-3-m {         outline-width: 3px; }
  .ow-4-m {         outline-width: 4px; }
  .ow-5-m {         outline-width: 5px; }
  .ow-6-m {         outline-width: 6px; }
  .ow-7-m {         outline-width: 7px; }
  .ow-8-m {         outline-width: 8px; }
  .ow-9-m {         outline-width: 9px; }
  .ow-10-m {        outline-width: 10px; }
  .ow-i-m {         outline-width: inherit; }
  .oo-1-m {         outline-offset: 1px; }
  .oo-2-m {         outline-offset: .25rem; }
  .oo-3-m {         outline-offset: .5rem; }
  .oo-4-m {         outline-offset: 1rem; }
  .oo-5-m {         outline-offset: 2rem; }
  .oo-i-m {         outline-offset: inherit; }
}

@media screen and (min-width: 64em)  {
  .oo--blk-l {      outline-color: $near-black; }
  .oo--dk-gry-l {   outline-color: $dark-gray; }
  .oo--md-gry-l {   outline-color: $mid-gray; }
  .oo--gray-l {     outline-color: $gray; }
  .oo--silver -l {  outline-color: $silver; }
  .oo--lt-slvr-l {  outline-color: $light-silver; }
  .oo--lt-gry-l {   outline-color: $light-gray; }
  .oo--near-wht-l { outline-color: $near-white; }
  .oo--wht-l {      outline-color: $white; }
  .os-none-l {      outline-style: none; }
  .os-dots-l {      outline-style: dotted; }
  .os-dash-l {      outline-style: dashed; }
  .os-solid-l {     outline-style: solid; }
  .os-double-l {    outline-style: double; }
  .os-groove-l {    outline-style: groove; }
  .os-ridge-l {     outline-style: ridge; }
  .os-inset-l {     outline-style: inset; }
  .os-outset-l {    outline-style: outset; }
  .os-inherit-l {   outline-style: inherit; }
  .ow-thin-l {      outline-width: thin; }
  .ow-med-l {       outline-width: medium; }
  .ow-thick-l {     outline-width: thick; }
  .ow-1-l {         outline-width: 1px; }
  .ow-2-l {         outline-width: 2px; }
  .ow-3-l {         outline-width: 3px; }
  .ow-4-l {         outline-width: 4px; }
  .ow-5-l {         outline-width: 5px; }
  .ow-6-l {         outline-width: 6px; }
  .ow-7-l {         outline-width: 7px; }
  .ow-8-l {         outline-width: 8px; }
  .ow-9-l {         outline-width: 9px; }
  .ow-10-l {        outline-width: 10px; }
  .ow-i-l {         outline-width: inherit; }
  .oo-1-l {         outline-offset: 1px; }
  .oo-2-l {         outline-offset: .25rem; }
  .oo-3-l {         outline-offset: .5rem; }
  .oo-4-l {         outline-offset: 1rem; }
  .oo-5-l {         outline-offset: 2rem; }
  .oo-i-l {         outline-offset: inherit; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

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

