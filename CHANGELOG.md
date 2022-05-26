# Change Log

## [0.0.21] 2022-05-26
### Improvements & Fixes

- Docker port is now `5085` (old one was `85`)
  - All starters  
- `.env` files - Update `ASSETS_ROOT` syntax
  - remove the comment
- Django Kits
  - Remove Unipath Dependency (not compiling on Ubuntu)
  - Fallback to `3.2.13` 
    - for a larger cross-platform compatibility
- Flask Kits
  - Fallback to `WTForms==3.0.0 (larger cross-platform compatibility)

## [0.0.20] 2022-05-24
### Improvements & Fixes

- Fixes
  - `Volt Dashboard` - Jinja Template Folder
  - CDN Path for `Jinja/Flask` was broken 

## [0.0.19] 2022-05-24
### Improvements & Fixes 

- ALL Kits Migrated to support CDN
  - Jinja
  - Flask
  - Django
- Django Codebase Improvements
  - Added CDN Support
- Flask Codebase Improvements
  - Added CDN Support
- Jinja Codebase Improvements
  - Codebase refactoring
  - Added CDN Support
- UI Update: Soft UI Dashboard 1.0.5

## [0.0.18] 2022-05-22
### Improvements

- Patch `MVC Django` DB Settings

## [0.0.17] 2022-05-20
### Improvements

- READMEs update (all products)
- Generator - Improve Error Checking 

## [0.0.16] 2022-05-20
### Improvements

- Integrate `Black Dashboard`

## [0.0.15] 2022-05-19
### Improvements

- Integrate `Material Dashboard (BS5)`

## [0.0.14] 2022-05-18
### Improvements

- Sources are ZIPped
  - available for instant download
- Added Redirects into generated `apps` folder  

## [0.0.13] 2022-05-18
### Improvements

- Improve the READMEs

## [0.0.12] 2022-05-17
### Improvements

- Integrate `Soft UI Design`
- Integrate `Pixel Lite`


## [0.0.11] 2022-05-17
### Improvements

- Integrate `Star Admin`

## [0.0.10] 2022-05-11
### Improvements

- Integrate `Material Kit`
- Patch `MVC Django` generator

## [0.0.9] 2022-05-11
### Improvements

- Update READMEs (all products)

## [0.0.8] 2022-05-08
### Improvements

- Patch `Flask` Generation Flow

## [0.0.7] 2022-05-04
### Improvements

- AdminLTE Working
  - `Jinja` / `Flask` & `Django` 
- Code is saved in GH

## [0.0.6] 2022-03-05

- Tag for future reference

## [0.0.5] 2022-02-18
### Improvements

- Added Flask DB customization
  - SQLite, MySql, PgSQL

## [0.0.4] 2022-02-16
### Improvements

- dummy 

## [0.0.3] 2022-02-16
### Fixes & Improvements

- Update All tasks
- Fix "active tasks" management
- Fix `server overloaded` case

## [0.0.2] 2022-02-15
### Fixes

- Patch all `task` management helpers
- Update `celery_testme` for state consistency 
- Added more helpers

## [0.0.1] 2022-02-15
### Initial release

- Tasks executed ok on Ubuntu
