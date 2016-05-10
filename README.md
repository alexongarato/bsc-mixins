# basic-sass-css3-mixins
A basic, clean and minimalist SASS CSS3 Mixin library.

## Import
```css3
@import "basic-sass-css3-mixins/basic-sass-css3-mixins";
```

## Usage

```css3
@include transition(background-color 0.1s, opacity 0.3s);
```
```css3
@include placeholder(#ffffff, italic);
```
```css3
@include reset(); /*provides basic properties reset*/
```
```css3
@include mobile-reset(); /*provides basic mobile properties reset for webapps*/
```
```css3
@include font-face("Open Sans", "OpenSans-Regular", $version:5);
```
```css3
@include border-radius(20%);
```
```css3
@include background-opacity(#cccccc, $opacity: 0.3);
```
```css3
@include clip-path(polygon(nonzero, 1.05% 52%, 2.05% 3%, 31.85% 3%, 52.4% 8%, 79.45% 6%, 99.3% 2%, 99.3% 95%, 73.65% 101%, 48.65% 98%, 22.25% 97%, 3.75% 100%));
```
```css3
@include radio-button-image-replacement(#ff0000); /* radio button image replacement */
```
