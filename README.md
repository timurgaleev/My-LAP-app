timurgaleev/my-lap-app
==========

This Docker container implements a last generation LAMP stack and a Postfix service to allow sending emails through PHP [mail()](http://php.net/manual/en/function.mail.php) function.

Includes components:

 * Ubuntu 16.04
 * Apache HTTP Server 2.4
 * Postfix 2.11
 * PHP 7
 * PHP modules
 	* php-bz2
	* php-cgi
	* php-cli
	* php-common
	* php-curl
	* php-dbg
	* php-dev
	* php-enchant
	* php-fpm
	* php-gd
	* php-gmp
	* php-imap
	* php-interbase
	* php-intl
	* php-json
	* php-ldap
	* php-mcrypt
	* php-odbc
	* php-opcache
	* php-pgsql
	* php-phpdbg
	* php-pspell
	* php-readline
	* php-recode
	* php-snmp
	* php-sqlite3
	* php-sybase
	* php-tidy
	* php-xmlrpc
	* php-xsl
 * Development tools
	* git
	* composer
	* npm / nodejs
	* bower
	* vim
	* tree
	* nano
	* ftp
	* curl

Installation from [Docker registry hub](https://registry.hub.docker.com/u/timurgaleev/my-lap-app).
----

You can download the image using the following command:

```bash
docker pull timurgaleev/my-lap-app
```

TIMEZONE
----

* Variable name: DATE_TIMEZONE
* Default value: UTC
* Accepted values: Any of PHP's [supported timezones](http://php.net/manual/en/timezones.php)
* Description: Set php.ini default date.timezone directive and sets MariaDB as well.


Use cases
----

```
	docker run -i -t --rm timurgaleev/my-lap-app bash
```
