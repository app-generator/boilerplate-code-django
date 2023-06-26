# Change Log

## [2.0.3] 2023-03-22
### Changes

- Bump UI: [Django Theme Material Kit](https://github.com/app-generator/django-theme-material-kit) `v1.0.18`
- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom-index` sample
- `Fix Docker` Execution
  - `Update Settings`: ALLOWED_HOSTS, CSRF_TRUSTED_ORIGINS `sections`

## [2.0.2] 2022-06-06
### Improvements

- Use generated version
  - Timestamp: `2022-06-06 13:47`
  - Build ID: `295d18b1-ccb5-49b1-bb79-8833ab377dd9`

## [2.0.1] 2022-06-06

- Tag latest `manual` coded version 

## [2.0.0] 2022-01-17
### Improvements

- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.7] 2021-12-08 
### Improvements (Minor)

- Gulp Scripts: Update the call of `gulp-sass` 

## [1.0.6] 2021-09-15 
### Improvements

- Codebase update
  - `assets` & `templates` moved to `apps` folder
  - `apps/base` renamed to `apps/home`

## [1.0.5] 2021-09-10
### Improvements, Bug fixing

- Dependencies update (all packages) 
  - Django==3.2.6 (latest stable version)
- Codebase:
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update
- UI: Pixel Lite v4.0.0  
- Tooling: Added Gulp SCSS compilation scripts
  - Help can be found on README -> `Recompile CSS` section
- Fixes:
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)  
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker

## [1.0.4] 2021-01-04
### Bug fixing

- Read properly the `.env` variables. Impacted file(s):
    - Impacted file: **core/settings.py**

## [1.0.3] 2021-01-01
### Bug fixing, Improvements

- 2021-01-01 - Improvements
    - Update login form label
    - Inject the current page name in view (segment variable) 

- 2020-06-28 - Update the UI Kit
    - Quick UI KIt by Webpixels

- Patch #3 - Whitenoise Fix - Wrong positioning in 'core/settings.py'
    - WhiteNoiseMiddleware must be positioned right after SecurityMiddleware
    - Impacted file: **core/settings.py** / MIDDLEWARE section

## [1.0.2] 2020-06-18
### Bug fixing, Improvements

- Patch #1 - Error when access `admin` path (no trailing slash)
- Update Sample UI Kit - [Neumorphism UI](https://themesberg.com/product/ui-kits/neumorphism-ui) by Themesberg

## [1.0.1] 2020-05-30
### Bug fixing, Improvements

- Add CHANGELOG.md to track all changes
- Patch Error-404.html not used in all contexts
- Rename error pages: error-40X become page-40X
- Update LICENSE file - added more information regarding the app usage

## [1.0.0] 2020-02-07
### Initial Release
