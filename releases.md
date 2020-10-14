# Release Notes

- [Simple Blog 1.8](#version_1_8)
- [Simple Blog 1.7](#version_1_7)
- [Simple Blog 1.6](#version_1_6)
- [Simple Blog 1.5](#version_1_5)
- [Simple Blog 1.4](#version_1_4)
- [Simple Blog 1.3](#version_1_3)
- [Simple Blog 1.2](#version_1_2)
- [Simple Blog 1.1](#version_1_1)

## Simple Blog 1.8
### Oct 14, 2020
- Fix multi-language with Ajax.
- Fix views count.
- Update contact form with Ajax.
- Update email encryption settings.
- Improve Recaptcha: add an option to hide v3 badge.
- Improve export posts to csv, excel.
- Improve theme UI.
- Refactor code.

## Simple Blog 1.7
### 15-09-2020
- Update to Laravel version 7.28
- Update homepage & blog page settings. Now, it's moved into Appearance -> Theme options.
- Move settings for Cookie Consent into Appearance -> Theme options.
- Add settings for watermark. Now, you can add watermark by changing setting in Admin -> Settings -> Media.
- Allow to change permalink in Admin -> Settings -> Permalinks.
- Add language settings. Allow to set default language in Admin -> Settings -> General.
- Allow admin to login using email or username.
- Optimize queries to make site loads faster.
- Update UI.
- Refactor code.
- Fix webpack.mix.js config, issue with path on Windows.
- Fix assets path.
- Fix copy folder in Admin -> Media.

## Simple Blog 1.6
### 05-08-2020
- Upgrade to the latest Laravel framework version 7.22.
- Deprecated some media functions: `is_image`, `get_image_url`, `get_object_image`, `rv_media_handle_upload`. 
  Replacements: `RvMedia::isImage()`, `RvMedia::getImageUrl()`, `RvMedia::handleUpload()`.
- Add support **Digital Ocean Spaces**.
- Fix timezone, it doesn't work before.
- Fix filter posts.
- Update email settings. Add support **SES**, **Postmark**, **Array**, **Log**.
- Improve performance & refactor source code.
- Improve license system, make it works better.


<a name="version_1_5"></a>
### 03-07-2020

- Update to the latest Laravel version 7.18.
- Optimize database queries.
- Add support Recaptcha v3.
- Improve cookie consent.
- Fix bugs plugin Language.
- Add default open graph image.
- Improve admin UI.
- Refactor code.

<a name="version_1_4"></a>
### 29-05-2020

- Update to the latest Laravel version 7.13.
- Improve media module: support upload chunk size.
- Improve email system.
- Move `js-validation` package to `core`.
- Upgrade jQuery to v3.5.1 and Bootstrap 4.5.0.
- Improve admin UI.
- Refactor code.

<a name="version_1_3"></a>
### 01-05-2020

- Update to the latest Laravel version 7.8.
- Refactor code & optimize performance.
- Add backup commands:
    - php artisan cms:backup:create
    - php artisan cms:backup:restore
    - php artisan cms:backup:remove
    - php artisan cms:backup:list
- Fix image's watermark.
- Change default avatar, remove Gravatar as default avatar.
- Fix widget & plugin language.
- Remove package `davejamesmiller/laravel-breadcrumbs`, build own breadcrumbs.
- Fix theme options when using `editor` field.

<a name="version_1_2"></a>
### 29-03-2020
- Update to the latest Laravel version 7.3.
- Add plugin Translation.
- Improve plugin language. When add/remove a language, it also adds/removes language files in /resources/lang.
- Improve source code.
- Update UI.
- Refactor code.

<a name="version_1_1"></a>
### 2020-03-11
- Update to latest Botble CMS 5.2 (using Laravel framework 7.x)
- Improve source code.
- Add captcha to contact form.
- Improve UI.

<a name="version_1_0"></a>
### 2020-02-13
- Initial release version 1.0
