# Heroku Static Site

This is an example for creating your own static sites on Heroku with a minimum of effort.

## Steps

1. Create an `index.php` file like the one you see [here](https://github.com/obfuscurity/heroku-static-site/blob/master/index.php).
1. Create a Heroku app (`heroku create -s cedar`).
1. Commit your `index.php` file and push it to your Heroku app.

## How Does It Work?

Simple. Heroku hosts PHP apps by launching them with their own Apache process inside a dyno. All you have to do is use the `php` extension so that Heroku thinks it's just another PHP app.

## Example

[My own static site](http://heroku-static-site.herokuapp.com/)
