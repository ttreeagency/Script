[![BSD License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![Latest Stable Version](https://poser.pugx.org/ttree/script/version)](https://packagist.org/packages/ttree/script)

# Script Fusion Objects

This package contains Fusion objects to work with Script HTML tags in your Flow Framework and Neos CMS project.

## Available Objects

### Ttree.StyleSheet:Resource

Generate a HTML script element in HTML5:

    stylesheets.main = Ttree.Script:Resource {
        uri = 'resource://Your.Package/Public/Scripts/Main.js'
    }

### Ttree.StyleSheet:External

Generate a HTML script element in HTML5:

    stylesheets.main = Ttree.Script:External {
        uri = 'http://www.domain.com/main.js'
    }

## Acknowledgments

Development sponsored by [ttree ltd - neos solution provider](http://ttree.ch).

We try our best to craft this package with a lots of love, we are open to sponsoring, support request, ... just contact us.

## License

The MIT License (MIT). Please see [LICENSE](LICENSE) for more information.
