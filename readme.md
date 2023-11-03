# PHP STRIKE BACK.

I am back into PHP and so much things have changed. Now it's all about symfony and composer.

## Compile an additional extension

Check out https://medium.com/@keithchasen/how-to-install-latest-php-with-postgresql-pdo-driver-using-phpenv-and-run-it-on-apache-and-nginx-86cd6278a79

In a nutshell, according to your PHP version:

```bash
export PHP_VERSION=8.2.11
cd /tmp
wget http://php.net/distributions/php-$PHP_VERSION.tar.gz
tar -xvzf php-$PHP_VERSION.tar.gz
# ...
cd php-$PHP_VERSION/ext/
phpize
```
