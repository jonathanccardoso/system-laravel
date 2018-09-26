# System-Laravel
Introduction to laravel

## Requirements
- php: adding some mindful (in docs)
- cmder: windows emulator (promt command)
- artisan: the command console
- composer: php package manager
- ide: phpStorm or atom

## Installation
- composer create-project --prefer-dist laravel / laravel 'name-project' 5.3
- be aware if you generated a key 'php artisan key: generate'
- run served from php: php artisan serves
- one of the most important archives:
.env - can set up databases, app_key, site address, email settings

## Server
- .env will not upload next to server (production)
- 'name-project' / config all configuration part

## directories
- main: / app
   - user.php is the system models
   - / middleware token authentications
   - / providers configuration files
- routes
   - definition of routes via web (web.php) and server (api.php)
- data base
   - facilitator folders in database management
- public: root folder
- resources
   - / views visual part of system layouts 'blade.php'

## System
- resources
   - welcome.blade.php // o index
- add controller
   - php artisan make: controller 'Site \ HomeController' (create folder'site 'and controller name' HomeController ')
- userADM
   - / database / seeds /
     - create user php artisan make: seed UserSeeder
     - run after configured all seeds php artisan db: seed
- Login
   - php artisan make: auth (create login system with bootstrap) or
   - create LoginController
   - configure get and post login path
