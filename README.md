# A simple PHP login script, in one file

A simple, but secure PHP login script in one file and a flat-file SQLite database.
No installation needed, ready to go in under 60seconds. Uses the ultra-modern & future-proof PHP 5.5.
BLOWFISH hashing/salting functions (includes the official PHP 5.3 & PHP 5.4 compatibility pack, which makes those
functions available in those versions too). Follow the project on **[Twitter](https://twitter.com/simplephplogin)**,
**[Facebook](https://www.facebook.com/pages/PHP-Login-Script/461306677235868)** or
**[Google+](https://plus.google.com/104110071861201951660)** and have a look on the official support blog
**[Dev Metal](http://www.dev-metal.com)**. Ask questions in the [Official Support Forum](http://109.75.177.79/forum/).

TODO: part of the php-login project

1. **One-file version:** Full login script in one file. Uses a one-file SQLite database (no MySQL needed) and PDO. Features: Register, login, logout.
2. **Minimal version** All the basic functions in a clean file structure, uses MySQL and mysqli. Register, login, logout.
3. **Professional version** Everything comes with a professional MVC framework structure, perfect for building
   real applications. Additional features like: URL rewriting, professional usage of controllers and actions, PDO, MySQL,
   mail sending via PHPMailer (SMTP or PHP's mail() function/linux sendmail), user profile pages, public user profiles,
   gravatars and local avatars, account upgrade/downgrade etc.

### Live-demo

[Click here to see a live demo](http://php-login.net/demo1.html) or [here to see the server's phpinfo()](http://109.75.177.79:80/).

### Requirements

- PHP 5.3.7+

### Installation

TODO!!!

A very detailed guideline [here in this blog post](http://www.dev-metal.com/how-to-install-php-login-nets-0-one-file-login-script-on-ubuntu/).

Call the install script via `_install.php`, which will create a `users.db` file right in the `database` folder. That's it.
Please note that the `database` folder needs to be writable and you need to have the SQLite extension activated in PHP.

### Useful links

- [How to install SQLite and Ubuntu and Debian](http://www.dev-metal.com/how-to-install-sqlite-driver-for-php-in-ubuntu-debian/)
- [How to use PDO](http://wiki.hashphp.org/PDO_Tutorial_for_MySQL_Developers)
- [A little guideline on how to use the PHP 5.5 password hashing functions and it's "library plugin" based PHP 5.3 & 5.4 implementation](http://www.dev-metal.com/use-php-5-5-password-hashing-functions/)

### How this script works

TODO (also explain the files and folders)

### License

Licensed under [MIT](http://www.opensource.org/licenses/mit-license.php).

### Official Support Blog: [dev-metal.com](http://www.dev-metal.com)

Have a look on my PHP blog, highly relevant to the login script !

### Support / Donate

If you think this script is useful and saves you a lot of work, then think about supporting the project by

1. Donating via [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=P5YLUK4MW3LDG)
   or [GitTip](https://www.gittip.com/Panique/)
2. Renting your next server at [DigitalOcean](https://www.digitalocean.com/?refcode=40d978532a20).
   SSD servers for $5+ per month or $0.007 per hour (!). PHP-MVC will get a small reward for every new customer.
3. Contributing to this project. Feel free to improve this project with your skills.

### Contribute

Please commit only in develop branch. The master branch will always contain a stable version.

### Author available for hire

I'm available for freelance work. Remote worldwide or locally around Central Europe. Drop me a line if you like.

TODO badge