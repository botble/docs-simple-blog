# Upgrade Guide

- [Upgrade to 1.8](#version_1_8)
- [Upgrade to 1.7](#version_1_7)
- [Upgrade to 1.6](#version_1_6)
- [Upgrade to 1.5](#version_1_5)
- [Upgrade to 1.4](#version_1_4)
- [Upgrade to 1.3](#version_1_3)
- [Upgrade to 1.2](#version_1_2)

<a name="version_1_8"></a>
## Upgrade to version 1.8

- Override folder `app`, `config`, and `platform` from the latest version.

- For developers:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    - Delete folder `public/vendor` and run command `php artisan vendor:publish --tag=cms-public --force`
    - Delete folder `public/themes` and run command `php artisan cms:theme:assets:publish`
    - Run command `php artisan vendor:publish --tag=cms-lang --force` to update translations.
    - Run `php artisan optimize:clear` to clear cache.
    
- For non-developers:
    - Override folder `public/themes`, `public/vendor`, `bootstrap`, `vendor` from the latest version.
    - Delete all files in `storage/framework/views` and `storage/framework/cache`.
    - Go to Admin -> Translations -> Admin translations then click on `Import group` to update translations.
    
<a name="version_1_7"></a>
## Upgrade to version 1.7

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
<a name="version_1_6"></a>
## Upgrade to version 1.6

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
<a name="version_1_5"></a>
## Upgrade to version 1.5

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
<a name="version_1_4"></a>
## Upgrade to version 1.4

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
<a name="version_1_3"></a>
## Upgrade to version 1.3

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
<a name="version_1_2"></a>
## Upgrade to version 1.2

- Override folder `app`, `config`, `platform`, `public/themes`, `public/vendor` and `resources/lang` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
    
- [Upgrade to 1.1](#version_1_1)

<a name="version_1_1"></a>
## Upgrade to version 1.1

- Override folder `app`, `config`, `platform`, `public/themes` and `public/vendor` from the latest version.

- For developer:
    - Update file `composer.json` and `composer.lock` from new source code.
    - Delete folder `/vendor` then run `composer install` to upgrade vendor packages.
    
- For non-developer:
    - Override folder `/vendor` from the latest version.
