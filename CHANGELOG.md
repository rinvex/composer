# Rinvex Composer Change Log

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](CONTRIBUTING.md).


## [v5.0.3] - 2020-12-29
- Rename core_modules to always_active
- Add get method to ModuleManifest class for retrieving module attributes

## [v5.0.2] - 2020-12-27
- Apply fixes from StyleCI
- Tweak and optimize module and custom composer installer
- Enable StyleCI risky mode

## [v5.0.1] - 2020-12-25
- Add support for PHP v8

## [v5.0.0] - 2020-12-22
- Upgrade to Laravel v8 & composer v2

## [v4.2.2] - 2020-08-29
- Tweak module loading logic to fix existing config override

## [v4.2.1] - 2020-08-29
- Tweak module loading logic to fix existing config override

## [v4.2.0] - 2020-08-04
- Add ability to autoload/unload installed/uninstalled modules

## [v4.1.0] - 2020-06-15
- Drop PHP 7.2 & 7.3 support from travis

## [v4.0.5] - 2020-04-12
- Fix ServiceProvider registerCommands method compatibility

## [v4.0.4] - 2020-04-09
- Tweak artisan command registration
- Refactor publish command and allow multiple resource values

## [v4.0.3] - 2020-04-04
- Fix namespace issue

## [v4.0.2] - 2020-04-04
- Enforce consistent artisan command tag namespacing
- Enforce consistent package namespace
- Drop laravel/helpers usage as it's no longer used

## [v4.0.1] - 2020-03-20
- Convert into bigInteger database fields
- Add shortcut -f (force) for artisan publish commands
- Fix migrations path

## [v4.0.0] - 2020-03-15
- Upgrade to Laravel v7.1.x & PHP v7.4.x

## [v3.0.1] - 2020-03-13
- Tweak TravisCI config
- Drop using global helpers
- Update StyleCI config

## [v3.0.0] - 2019-09-23
- Upgrade to Laravel v6 and update dependencies

## [v2.1.1] - 2019-06-03
- Enforce latest composer package versions

## [v2.1.0] - 2019-06-02
- Update composer deps
- Drop PHP 7.1 travis test

## [v2.0.0] - 2019-03-03
- Rename environment variable QUEUE_DRIVER to QUEUE_CONNECTION
- Require PHP 7.2 & Laravel 5.8
- Apply PHPUnit 8 updates
- Tweak and simplify FormRequest validations

## [v1.0.2] - 2018-12-22
- Add missing console/command namespace

## [v1.0.1] - 2018-12-22
- Add publish command
- Update composer dependencies
- Add PHP 7.3 support to travis

## [v1.0.0] - 2018-10-01
- Enforce Consistency
- Support Laravel 5.7+
- Rename package to rinvex/laravel-composer

## [v0.0.2] - 2018-09-22
- Update travis php versions
- Drop StyleCI multi-language support (paid feature now!)
- Update composer dependencies
- Prepare and tweak testing configuration
- Highlight variables in strings explicitly
- Update StyleCI options
- Update PHPUnit options

## v0.0.1 - 2018-02-18
- Tag first release

[v5.0.3]: https://github.com/rinvex/laravel-composer/compare/v5.0.2...v5.0.3
[v5.0.2]: https://github.com/rinvex/laravel-composer/compare/v5.0.1...v5.0.2
[v5.0.1]: https://github.com/rinvex/laravel-composer/compare/v5.0.0...v5.0.1
[v5.0.0]: https://github.com/rinvex/laravel-composer/compare/v4.2.2...v5.0.0
[v4.2.2]: https://github.com/rinvex/laravel-composer/compare/v4.2.1...v4.2.2
[v4.2.1]: https://github.com/rinvex/laravel-composer/compare/v4.2.0...v4.2.1
[v4.2.0]: https://github.com/rinvex/laravel-composer/compare/v4.1.0...v4.2.0
[v4.1.0]: https://github.com/rinvex/laravel-composer/compare/v4.0.5...v4.1.0
[v4.0.5]: https://github.com/rinvex/laravel-composer/compare/v4.0.4...v4.0.5
[v4.0.4]: https://github.com/rinvex/laravel-composer/compare/v4.0.3...v4.0.4
[v4.0.3]: https://github.com/rinvex/laravel-composer/compare/v4.0.2...v4.0.3
[v4.0.2]: https://github.com/rinvex/laravel-composer/compare/v4.0.1...v4.0.2
[v4.0.1]: https://github.com/rinvex/laravel-composer/compare/v4.0.0...v4.0.1
[v4.0.0]: https://github.com/rinvex/laravel-composer/compare/v3.0.1...v4.0.0
[v3.0.1]: https://github.com/rinvex/laravel-composer/compare/v3.0.0...v3.0.1
[v3.0.0]: https://github.com/rinvex/laravel-composer/compare/v2.1.1...v3.0.0
[v2.1.1]: https://github.com/rinvex/laravel-composer/compare/v2.1.0...v2.1.1
[v2.1.0]: https://github.com/rinvex/laravel-composer/compare/v2.0.0...v2.1.0
[v2.0.0]: https://github.com/rinvex/laravel-composer/compare/v1.0.2...v2.0.0
[v1.0.2]: https://github.com/rinvex/laravel-composer/compare/v1.0.1...v1.0.2
[v1.0.1]: https://github.com/rinvex/laravel-composer/compare/v1.0.0...v1.0.1
[v1.0.0]: https://github.com/rinvex/laravel-composer/compare/v0.0.2...v1.0.0
[v0.0.2]: https://github.com/rinvex/laravel-composer/compare/v0.0.1...v0.0.2
