# A simple PHP login script (in one file)

A simple, but secure PHP login script in one file and a flat-file SQLite database.
No installation needed, ready to go in under 60 seconds. Uses the ultra-modern & future-proof PHP 5.5.
BLOWFISH hashing/salting functions (includes the official PHP 5.3 & PHP 5.4 compatibility pack, which makes those
functions available in those versions too). Follow the project on **[Twitter](https://twitter.com/simplephplogin)**,
**[Facebook](https://www.facebook.com/pages/PHP-Login-Script/461306677235868)** or
**[Google+](https://plus.google.com/104110071861201951660)** and have a look on the official support blog
**[Dev Metal](http://www.dev-metal.com)**. Ask questions in the [Official Support Forum](http://109.75.177.79/forum/).

**This script is part of the php-login project, a collection of 4 different login scripts**.
See [php-login.net](http://www.php-login.net) for more info.
*Please note: The entire project is currently in a restructuring process, look into https://github.com/panique/php-login for the latest stable version and install tutorials.*

1. **One-file version:** Full login script in one file. Uses a one-file SQLite database (no MySQL needed) and PDO.
   Features: Register, login, logout.
   https://github.com/panique/php-login-one-file
2. **Minimal version** All the basic functions in a clean file structure, uses MySQL and mysqli.
   Register, login, logout.
   https://github.com/panique/php-login-minimal
3. **Advanced version** Similar to the minimal version, but full of features.
   Uses PDO, Captchas, mail sending via SMTP and much more.
   https://github.com/panique/php-login-advanced
3. **Professional version** Everything comes with a professional MVC framework structure, perfect for building
   real applications. Additional features like: URL rewriting, professional usage of controllers and actions, PDO, MySQL,
   mail sending via PHPMailer (SMTP or PHP's mail() function/linux sendmail), user profile pages, public user profiles,
   gravatars and local avatars, account upgrade/downgrade etc., login via Facebook, Composer integration, etc.
   https://github.com/panique/php-login

## Live-demo

**Live demo [here](http://php-login.net/demo1.html), live demo's phpinfo() [here](http://109.75.177.79:80/)**

## Requirements

- PHP 5.3.7+ (with PDO and SQLite extension activated)

## Installation (quick setup)

Call the install script via `_install.php`, which will create a `users.db` file right in the `database` folder. That's it.
Please note that the `database` folder needs to be writable and you need to have the SQLite extension activated in PHP.

## Installation (very detailed setup)

A very detailed guideline [here in this blog post](http://www.dev-metal.com/how-to-install-php-login-nets-0-one-file-login-script-on-ubuntu/).

## Useful links

- [How to install SQLite and Ubuntu and Debian](http://www.dev-metal.com/how-to-install-sqlite-driver-for-php-in-ubuntu-debian/)
- [How to use PDO](http://wiki.hashphp.org/PDO_Tutorial_for_MySQL_Developers)
- [A little guideline on how to use the PHP 5.5 password hashing functions and it's "library plugin" based PHP 5.3 & 5.4 implementation](http://www.dev-metal.com/use-php-5-5-password-hashing-functions/)

## How this script works

TODO (also explain the files and folders)

## License

Licensed under [MIT](http://www.opensource.org/licenses/mit-license.php).

## Support / Donate

If you think this script is useful and saves you a lot of work, then think about supporting the project by donating via
[PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=P5YLUK4MW3LDG)
or [GitTip](https://www.gittip.com/Panique/) or renting your next server at
[DigitalOcean](https://www.digitalocean.com/?refcode=40d978532a20). DigitalOcean offers SSD servers for $5+ per month
or $0.007 per hour (!). Or, if you feel skilled, contribute to this project (features, bugfixes, etc).

## Contribute

Please commit only in develop branch. The master branch will always contain a stable version.

## Stats

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/panique/php-login-one-file/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

