[![Latest Stable Version](https://poser.pugx.org/jonnitto/textwithplyr/v/stable)](https://packagist.org/packages/jonnitto/textwithplyr)
[![Total Downloads](https://poser.pugx.org/jonnitto/textwithplyr/downloads)](https://packagist.org/packages/jonnitto/textwithplyr)
[![License](https://poser.pugx.org/jonnitto/textwithplyr/license)](LICENSE)
[![GitHub forks](https://img.shields.io/github/forks/jonnitto/Jonnitto.TextWithPlyr.svg?style=social&label=Fork)](https://github.com/jonnitto/Jonnitto.TextWithPlyr/fork)
[![GitHub stars](https://img.shields.io/github/stars/jonnitto/Jonnitto.TextWithPlyr.svg?style=social&label=Stars)](https://github.com/jonnitto/Jonnitto.TextWithPlyr/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/jonnitto/Jonnitto.TextWithPlyr.svg?style=social&label=Watch)](https://github.com/jonnitto/Jonnitto.TextWithPlyr/subscription)
[![GitHub followers](https://img.shields.io/github/followers/jonnitto.svg?style=social&label=Follow)](https://github.com/jonnitto/followers)
[![Follow Jon on Twitter](https://img.shields.io/twitter/follow/jonnitto.svg?style=social&label=Follow)](https://twitter.com/jonnitto)

# Jonnitto.TextWithPlyr Package for Neos CMS

This package is an extension for [Jonnitto.Plyr](https://github.com/jonnitto/Jonnitto.Plyr). With this plugin, you get some new nodes who include a text field into plyr.

## Installation

Most of the time you have to make small adjustments to a package (e.g. configuration in `Settings.yaml`). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under `Packages/Sites/`. To install it correctly go to your theme package (e.g.`Packages/Sites/Foo.Bar`) and run following command:

```bash
composer require jonnitto/textwithplyr --no-update
```

The `--no-update` command prevent the automatic update of the dependencies. After the package was added to your theme `composer.json`, go back to the root of the Neos installation and run `composer update`. Et voilà! Your desired package is now installed correctly.

## License

Licensed under MIT, see [LICENSE](LICENSE)
