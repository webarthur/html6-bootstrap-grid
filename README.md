# HTML6 Bootstrap Grid

HTML6 grid based on Bootstrap CSS Framework.

## Advantages

* Semantic
* More clean
* Less code
* DRY styled code (Don't Repeat Yourself)
* Build with SASS

## How To:

You can use basically the same classes of Bootstrap without "col-" class prefixes. You can apply cols attribute for any tags. There is no "xm-" classes, just put the numbers of columns and enjoy!

```html
<!-- Semantic and small classes -->
<row>
  <div cols="12">old .col-xs-12 class</div>
  <div cols="6">old .col-xs-6 class</div>
</row>

<!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
<row>
  <div cols="6 md-4">lorem ipsum</div>
  <div cols="6 md-4">lorem ipsum</div>
  <div cols="6 md-4">lorem ipsum</div>
</row>

<!-- Columns are always 50% wide, on mobile and desktop -->
<row>
  <div cols="6">lorem ipsum</div>
  <div cols="6">lorem ipsum</div>
</row>
```

### The old way >={

```html
<!-- Stack the columns on mobile by making one full-width and the other half-width -->
<div class="row">
  <div class="col-xs-12 col-md-8">.col-xs-12 .col-md-8</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop -->
<div class="row">
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
  <div class="col-xs-6 col-md-4">.col-xs-6 .col-md-4</div>
</div>

<!-- Columns are always 50% wide, on mobile and desktop -->
<div class="row">
  <div class="col-xs-6">.col-xs-6</div>
  <div class="col-xs-6">.col-xs-6</div>
</div>
```

## [Author](http://araujo.cc)

* [Arthur Araújo](http://araujo.cc)

## [Creative Commons License](http://creativecommons.org/licenses/by-sa/4.0/)

Code released under Creative Commons Share-alike. It's free to copy, merge, publish and distribute without any limitations! =D

<i>"Simplicity is the ultimate sophistication" - Leonardo da Vinci</i>
