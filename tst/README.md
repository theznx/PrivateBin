Running unit tests
==================

In order to run these tests, you will need to install the following packages
and its dependencies:
* phpunit
* php5-gd
* php5-sqlite
* php5-xdebug

Example for Debian and Ubuntu:
```sh
$ sudo aptitude install phpunit php5-gd php5-sqlite php5-xdebug
```

To run the tests, just change into this directory and run phpunit:
```sh
$ cd PrivateBin/tst
$ phpunit
```
