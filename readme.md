# Laravel 5 requirements check

This code exists to validate if the server you are going to install Laravel meets the requirements for the project to run smoothly.

It is based on the Symfony's [check configuration file](http://svn.symfony-project.com/branches/1.4/data/bin/check_configuration.php), so the major credit goes to them.

## Usage

When you want to check the development environment, before installing Laravel, you must:

1. Upload the `check.php` and `.htaccess` files to your server root folder.
2. Access the `check.php` file from your favorite web browser.
3. Enjoy the report! ;-)

### Optional

If you want to check for Laravel 5.0 requirements, you can use the parameter like this:

```
http://server.com/check/check.php?5.0
```

## License

[Released under the MIT License (MIT)](http://www.opensource.org/licenses/mit-license.html)
