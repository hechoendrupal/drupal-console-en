# drupal-console-en

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To install Drupal Console package in other languages check the packages available at [https://packagist.org](https://packagist.org)


### Install Drupal Console

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. In order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,
 
To install Drupal Console launcher globally follow the instruction below. 

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps to setup your environment.

- [Project requirements](https://docs.drupalconsole.com/en/contributing/project-requirements.html)
- [Getting the project](https://docs.drupalconsole.com/en/contributing/getting-the-project.html)
- [Running the project](https://docs.drupalconsole.com/en/contributing/running-the-project.html)

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.
