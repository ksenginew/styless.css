# Styless.css

Minimal classless CSS framework for faster development.

<a href="issues/new?template=bug_report.md">Report bug</a>
·
<a href="issues/new?template=feature_request.md">Request feature</a>

## Quick start

Looking to quickly add Styless to your project? Use jsDelivr, a free open source CDN. Using a package manager or need to download the source files? Head to the downloads page.

### Installation

Copy-paste the stylesheet <link> into your <head> before all other stylesheets to load our CSS.

```html
<link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU"
    crossorigin="anonymous"
/>
```

### Starter template

Be sure to have your pages set up with the latest design and development standards. That means using an HTML5 doctype and including a viewport meta tag for proper responsive behaviors. Put it all together and your pages should look like this:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1" />

        <!-- Styless CSS -->
        <link
            href="https://cdn.jsdelivr.net/npm/styless@0.0.0/styless.min.css"
            rel="stylesheet"
            crossorigin="anonymous"
        />

        <!-- Optional code syntax highlighter -->
        <link
            href="https://cdn.jsdelivr.net/npm/prismjs@1.24.1/themes/prism.css"
            rel="stylesheet"
        />
        <script src="https://cdn.jsdelivr.net/npm/prismjs@1.24.1/components/prism-core.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/prismjs@1.24.1/plugins/autoloader/prism-autoloader.min.js"></script>

        <title>Hello, world!</title>
    </head>
    <body>
        <h1>Hello, world!</h1>
    </body>
</html>
```

## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](blob/main/.github/CONTRIBUTING.md) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](issues/new).

## Contributing

Please read through our [contributing guidelines](blob/main/.github/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

## Community

Get updates on Styless's development and chat with the project maintainers and community members.

-   Follow [@moonharelabs on Twitter](https://twitter.com/harelabs).

## Copyright and license

Code released under the [MIT License](blob/main/LICENSE).
