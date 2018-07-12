# LazyLoad

This is a customized [LazyLoad][1] package to be integrated in
[Contao Open Source CMS][2].

## Install

```
composer require heimrichhannot-contao-components/lazyload
```

## In use

* [Contao Speed Bunde][3]

## Config

Add the following to your config (keep keys to prevent double integration):

### Contao 4

```
$GLOBALS['TL_USER_CSS']['huh_components_lazyload'] = 'assets/lazyload/css/lazyload.min.css|static';
$GLOBALS['TL_JAVASCRIPT']['huh_components_lazyload'] = 'assets/lazyload/js/8/lazyload.min.js|static';
// or
$GLOBALS['TL_JAVASCRIPT']['huh_components_lazyload'] = 'assets/lazyload/js/10/lazyload.min.js|static';
```

### Contao 3

```
$GLOBALS['TL_USER_CSS']['huh_components_lazyload'] = 'assets/components/css/lazyload.css|static';
$GLOBALS['TL_JAVASCRIPT']['huh_components_lazyload'] = 'assets/components/js/8/lazyload.min.js|static';
// or 
$GLOBALS['TL_JAVASCRIPT']['huh_components_lazyload'] = 'assets/components/js/10/lazyload.min.js|static';
```



[1]: https://github.com/verlok/lazyload
[2]: https://contao.org
[3]: https://github.com/heimrichhannot/contao-speed-bundle
