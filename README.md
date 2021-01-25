<h1 align="center">Testing CI config</h1>

<p align="center">Trying to improve development practices that have, well, aged.</p>



## CI Links

### Travis CI

https://travis-ci.com/github/tomkyle/test-ci-configs
[![Build Status](https://img.shields.io/travis/com/tomkyle/test-ci-configs.svg?label=Travis%20CI)](https://travis-ci.org/tomkyle/test-ci-configs)

### Scrutinizer

https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/inspections
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/badges/quality-score.png)](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/)
[![Code Coverage](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/badges/coverage.png)](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/)
[![Build Status](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/badges/build.png)](https://scrutinizer-ci.com/g/tomkyle/test-ci-configs/)

### Coveralls

https://coveralls.io/github/tomkyle/test-ci-configs

## Unit tests and development

1. Copy `phpunit.xml.dist` to `phpunit.xml` 
2. Run [PhpUnit](https://phpunit.de/) like this:

```bash
$ composer test
# or
$ vendor/bin/phpunit
```


