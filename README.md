# Composer template for a basic GC project

[![Build Status](https://travis-ci.org/RabiaSajjad/basic.svg?branch=master)](https://travis-ci.org/RabiaSajjad/basic)

This project template provides a starter kit for managing your site
dependencies with [Composer](https://getcomposer.org/) with an
application of the [WET-BOEW GCWeb](https://github.com/wet-boew/GCWeb) theme.

## Usage

1. Install [composer](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx).

Optional - [Global composer installation](https://getcomposer.org/doc/00-intro.md#globally).
If skipping, you may need to replace `composer` with `php composer.phar` for your setup.

2. Create project

```
composer create-project opengov/basic-project:dev-master MYPROJECT --no-interaction
```

3. Install using interface, choose Basic as your installation profile. As an alternative, 
you can also use drush for installation

```
drush site:install basic
```

## What does the template do?

The template will setup:

1. Drupal core in `html/core` directory.
2. Profiles in `html/profiles` directory.
3. Contributed modules in `html/modules/contrib` directory.
4. Libraries for WET-BOEW in `html/libraries` directory.
5. Themes in `html/themes` directory and enables GCWeb as default theme.
6. `settings.php` and `services.yml` in `html/sites/default` directory. 
7. Drush in `vendor/bin/drush` directory.
8. DrupalConsole in `vendor/bin/drupal` directory.

