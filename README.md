# php-UnitTest-practice
This project is for learning phpUnitTests

## Installation (Windows)

<strong>you need have php installed in your local machine or use xamp for local server.</strong>

- create a folder where you want to test.
*Install php-unit in the folder by going into the floder in CMD and executing the following commend.

```
composer require --dev phpunit/phpunit
```
you need to configure the path of unit test as phpUnitTests, for this you need to run the following commend

```
@php "%~dp0vendor\phpunit\phpunit\phpunit" %* > phpunit.cmd
```
now test the phpunit commend by running

```
phpunit
```
