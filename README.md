<h1>B3Helper</h1>

<p>B3Helper is a library of responsive CSS classes for padding, margin and text-alignment based on Bootstrap 3 breakpoints:</p>

* XS: <= 767px
* SM: 768px - 991px
* MD: 992px - 1199px
* LG: >= 1200px

**B3Helper is NOT usable without Bootstrap 3.3.7.**

<h2>Installation</h2>

1. Download or Clone repository
2. Copy file css/b3helper.css into your project
3. Import B3Helper CSS into your HTML files via link tag


```
<link rel="stylesheet" type="text/css" href="path-to-your-css/b3helper.css">
```

<h2>Use</h2>

<h4>Padding</h4>

<p>Block with padding 0px on XS and SM (0 - 991px) and padding 50px on MD and LG (>= 992px):</p>

```
<div class="xs-p-0 md-p-50"></div>
```

<h4>Margin</h4>

<p>Block with margin 20px on XS (0 - 767px), margin 10px on SM and MD (768 - 1199px) and margin 30px on LG (>= 1200px):</p>

```
<div class="xs-m-20 sm-m-10 lg-m-30"></div>
```

<h4>Text alignment</h4>

<p>Paragraph with text aligned to left on XS, to center on SM, to right on MD and justified on LG:</p>

```
<p class="xs-t-l sm-t-c md-t-r lg-t-j">Text</p>
```