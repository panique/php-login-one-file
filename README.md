# php-login-one-file

A simple, but secure PHP login script in one file and a flat-file SQLite database.

No installation needed, ready to go in under 60 seconds. Uses the ultra-modern & future-proof PHP 5.5.
BLOWFISH hashing/salting functions (includes the official PHP 5.3 & PHP 5.4 compatibility pack, which makes these
functions available in these versions too). 

This script was originally part of the "php-login project", a collection of 4 different login scripts made in the 2012-2013 PHP era to give especially beginners and security-inexperienced users a set of basic auth functions that fitted the most modern password hashing standards possible. You know, this was the time when even major companies like SONY and LinkedIn used horrible outdated MD5-hashing for their passwords (or even saved everything in plain text) and when the big PHP frameworks didn't have proper user auth solution out-of-the-box.

[![Support the project](_installation/banner-host1plus.png)](https://affiliates.host1plus.com/ref/devmetal/36f4d828.html)

Find the other versions here:

**One-file version** (not maintained anymore)
Full login script in one file. Uses a one-file SQLite database (no MySQL needed) and PDO: Register, login, logout.
https://github.com/panique/php-login-one-file

**Minimal version** (not maintained anymore)
All the basic functions in a clean file structure, uses MySQL and mysqli. Register, login, logout.
https://github.com/panique/php-login-minimal

**Advanced version** (not maintained anymore)
Similar to the minimal version, but full of features. Uses PDO, Captchas, mail sending via SMTP and much more.
https://github.com/panique/php-login-advanced

**HUGE (professional version)** 
Quite professional MVC framework structure, useful for real applications. Additional features like: URL rewriting, mail sending via PHPMailer (SMTP or PHP's mail() function/linux sendmail), user profile pages, public user profiles, gravatars and local avatars, account upgrade/downgrade etc., OAuth2, Composer integration, etc.
https://github.com/panique/huge

## Requirements

- PHP 5.3.7+ (with PDO and SQLite extension activated)

## Installation (quick setup)

Run the install script `_install.php` in the `_installation` folder which will create a `users.db` file (the database).
That's it.

## Installation (very detailed setup)

A very detailed guideline [here in this blog post](http://www.dev-metal.com/how-to-install-php-login-nets-0-one-file-login-script-on-ubuntu/).

## Important security note

In the default setup the database - which is only a simple users.db file - can be downloaded directly.
To prevent this, change the path of your database file! A path that is not accessable by public is perfect.
The .htaccess in the project only works if you have set `AllowOverride` to `All` in your vhost / apache config.

## Short guide

The `index.php` does all the action, please look into the code for more info, everything is commented. The install script
`_install.php` creates a database (a file named `users.db`) right into the root folder. The `.htaccess` protects your
database file from being downloaded. The `password_compatibility_library.php` is only loaded automatically when you
use a PHP version older than 5.5 to add the new PHP 5.5 password hashing functions to these older PHP versions.
The `_debug.php` is a little helper tool, it simply echoes out the content of the database.

## Useful links

- [How to install SQLite and Ubuntu and Debian](http://www.dev-metal.com/how-to-install-sqlite-driver-for-php-in-ubuntu-debian/)
- [How to use PDO](http://wiki.hashphp.org/PDO_Tutorial_for_MySQL_Developers)
- [A little guideline on how to use the PHP 5.5 password hashing functions and it's "library plugin" based PHP 5.3 & 5.4 implementation](http://www.dev-metal.com/use-php-5-5-password-hashing-functions/)

## License

Licensed under [MIT](http://www.opensource.org/licenses/mit-license.php). You can use this script for free for any
private or commercial projects.

## Support

If you think this script is useful and saves you a lot of work, then please support the project by renting your new 
server at [Host1Plus](https://affiliates.host1plus.com/ref/devmetal/36f4d828.html) or 
[DigitalOcean](https://www.digitalocean.com/?refcode=40d978532a20), it's just $2 - $5.

## Contribute

Please commit only in *develop* branch). The *master* branch will always contain the stable version.
