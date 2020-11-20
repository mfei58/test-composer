# URL Scanner

Scan an array of URLs and report inaccessible URLs

## Install

Via Composer

``` bash
$ composer require modernphp/scanner
```

## Usage

``` php
$urls = [
    'http://www.apple.com',
    'http://php.net',
    'http://sdfssdwerw.org'
];
$scanner = new \Mfei\ModernPHP\Url\Scanner($urls);
print_r($scanner->getInvalidUrls());
```

## Testing

Tests unavailable.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [mfei58](https://github.com/mfei58)
- [All Contributors](https://github.com/mfei58/scanner/contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
