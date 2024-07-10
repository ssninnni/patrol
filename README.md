<p align="center">
    <img src="/art/logo.svg" height="80" alt="Patrol logo">
</p>
<p align="center">
    <img src="https://raw.githubusercontent.com/nunomaduro/patrol/master/docs/example.png" width="600" alt="Patrol">
    <p align="center">
        <a href="https://packagist.org/packages/nunomaduro/patrol"><img alt="Total Downloads" src="https://img.shields.io/packagist/dt/nunomaduro/patrol"></a>
        <a href="https://packagist.org/packages/nunomaduro/patrol"><img alt="License" src="https://img.shields.io/github/license/nunomaduro/patrol"></a>
    </p>
</p>

------

**Patrol** is an elegant command-line tool that keeps your PHP Project's dependencies in check.

## Installation / Usage

> **Requires [PHP 8.2+](https://php.net/releases/)**

First, install Patrol via the [Composer](https://getcomposer.org/) package manager:

```bash
composer require patrol/patrol --dev
```

Then, use the `patrol` binary:

```bash
./vendor/bin/patrol
```

You may also specify the directory that should be inspected:

```bash
./vendor/bin/patrol inspect ../another/project-directory
```

## License

Patrol is an open-sourced software licensed under the [MIT license](LICENSE.md).
