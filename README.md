[![BSD License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![Latest Stable Version](https://poser.pugx.org/ttree/script/version)](https://packagist.org/packages/ttree/script)

# Script Fusion Prototypes

This package contains Fusion prototypes to work with Script HTML tags in your Flow Framework and Neos CMS project.

## Available Objects

### Ttree.Script:Resource

Generate a HTML script element in HTML5:

    stylesheets.main = Ttree.Script:Resource {
        uri = 'resource://Your.Package/Public/Scripts/Main.js'
        cacheBusting = true
    }

You can disable HTTP cache busting by setting ```cacheBusting``` to ```false```.

Set ```inline``` to ```true``` to inline the content of the resource.

### Ttree.Script:External

Generate a HTML script element in HTML5:

    javascripts.main = Ttree.Script:External {
        uri = 'http://www.domain.com/main.js'
    }

## Acknowledgments

Development sponsored by [ttree ltd - neos solution provider](http://ttree.ch).

We try our best to craft this package with a lots of love, we are open to sponsoring, support request, ... just contact us.

## License

The MIT License (MIT). Please see [LICENSE](LICENSE) for more information.
