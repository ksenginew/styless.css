# 📖 Introduction
Get started with Styless, with jsDelivr and a template starter page.

## Quick start
Looking to quickly add Styless to your project? Use jsDelivr, a free open source CDN. Using a package manager or need to download the source files? Head to the [downloads](/downloads) page.

### Installation
Copy-paste the stylesheet `<link>` into your `<head>` before all other stylesheets to load our CSS.

```html
<link href="https://cdn.jsdelivr.net/npm/styless@0.0.0/styless.min.css" rel="stylesheet" crossorigin="anonymous">
```

### Starter template
Be sure to have your pages set up with the latest design and development standards. That means using an HTML5 doctype and including a viewport meta tag for proper responsive behaviors. Put it all together and your pages should look like this:
```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Styless CSS -->
    <link href="https://cdn.jsdelivr.net/npm/styless@0.0.0/styless.min.css" rel="stylesheet" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
For next steps, use our official [examples](/examples) to start.

## Important globals
Styless employs a handful of important global styles and settings that you’ll need to be aware of when using it, all of which are almost exclusively geared towards the normalization of cross browser styles. Let’s dive in.

### HTML5 doctype
Styless requires the use of the HTML5 doctype. Without it, you’ll see some funky incomplete styling, but including it shouldn’t cause any considerable hiccups.
```html
<!doctype html>
<html lang="en">
  ...
</html>
```
### Responsive meta tag
To ensure proper rendering and touch zooming for all devices, add the responsive viewport meta tag to your `<head>`.
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```
You can see an example of this in action in the starter template.

### Box-sizing
For more straightforward sizing in CSS, we switch the global box-sizing value from content-box to border-box. This ensures padding does not affect the final computed width of an element, but it can cause problems with some third-party software like Google Maps and Google Custom Search Engine.

On the rare occasion you need to override it, use something like the following:
```html
<div style="box-sizing: content-box;">
  ...
</html>
```

Learn more about [box model and sizing at CSS Tricks](https://css-tricks.com/box-sizing/).

### Normalize
For improved cross-browser rendering, we use [modern-normalize](https://github.com/sindresorhus/modern-normalize) to correct inconsistencies across browsers and devices while providing slightly more opinionated resets to common HTML elements.
