# [LambdaSpace](http://www.lambdaspace.gr/) - Drupal8 website for Thessaloniki's Hackerspace

This guide assumes you have a development server set up and able to run a Drupal8 installation. 
If not, [here](https://www.drupal.org/docs/develop/local-server-setup) you can find some guides on how to set up
a Drupal development environment on your machine.

This project uses composer template for Drupal projects [drupal-composer/drupal-project](https://github.com/drupal-composer/drupal-project). 
 
## Requirements

1. [Composer](https://getcomposer.org/) Dependency Manager for PHP
2. Git (optional but highly recommended)

## Installation

1. Git clone the repository or download it from github's user interface.
2. cd to the project
3. Install dependencies with composer "composer install", that will take a while.
4. Now you can see the Drupal installation screen in your browser.
5. In the root of our project there is database file 'db.sql' you can either install Drupal and then import
   the database or import the database and connect it with your Drupal installation.
6. You should have a working instance of LambdaSpace Drupal8 website.