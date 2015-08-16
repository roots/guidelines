# Roots Coding and Contributing Guidelines

## PHP

[PSR-2 coding style](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) with the following changes:

* 2 spaces indentation
* Opening and closing braces for functions and classes forced on the same line
* Forced newline after opening brace

Additional rules:

* Use `Roots\` namespace
* Use short array syntax
* Use short echo syntax

You can check if your contribution passes the styleguide by installing [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) and running the following in your project directory:

```bash
phpcs --standard=ruleset.xml --extensions=php --ignore=node_modules,bower_components,vendor -n -s .
```

## JavaScript

Every JavaScript contribution is run against the [Google JavaScript Styleguide](https://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml). You can check if your contribution passes the styleguide by installing [JSCS](http://jscs.info/) and running the following in your project directory:

```bash
npm run jscs
```
