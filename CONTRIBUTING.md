# Contributing

Contributions are **welcome** and will be fully **credited**.

We accept contributions via Pull Requests on [Github](https://github.com/edu-cat/educat).

## Pull Requests

- **Laravel Coding Standard** - The easiest way to apply the conventions is to use 
[Laravel Pint](https://github.com/laravel/pint) (included in the application).

- **Add [Pest](https://pestphp.com/) tests!** - Your patch won't be accepted if it doesn't have tests. Your code 
coverage should be _100%_. Use [Pest](https://pestphp.com/) (included in the application) to write your tests.

- **Static Code Analyze** - use [PHPStan](https://phpstan.org/) (included in the application) to check your code.
A violation will cause the build to fail, so please make sure there are no violations. We can't accept a patch 
if the build fails.

- **Document any change in behaviour** - Make sure the README and any other relevant documentation are kept up-to-date.

- **Consider our release cycle** - We try to follow SemVer. Randomly breaking public APIs is not an option.

- **Create topic branches** - Don't ask us to pull from your master branch.

- **One pull request per feature** - If you want to do more than one thing, send multiple pull requests.

- **Send coherent history** - Make sure each individual commit in your pull request is meaningful. 
If you had to make multiple intermediate commits while developing, please squash them before submitting.

- **Ensure tests pass!** - Please run the tests (see below) before submitting your pull request, 
and make sure they pass. We won't accept a patch until all tests pass.

- **Ensure no coding standards violations** - Please run [Laravel Pint](https://github.com/laravel/pint) using 
_Laravel Presets_ (see below) before submitting your pull request. A violation will cause the build to fail, 
so please make sure there are no violations. We can't accept a patch if the build fails.

## Running Laravel Pint

``` bash
$ composer style
```

## Running PHPStan

``` bash
$ composer analyze
```

## Running Tests

``` bash
$ composer tests
```

## Running Security Advisory

``` bash
$ composer sec-advisory
```

**Happy coding**!
