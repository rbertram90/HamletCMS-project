# HamletCMS Project

## About
A blogger style content management system for writing blog articles. Check out the wiki for documentation https://github.com/rbertram90/HamletCMS/wiki.

### Installation
1. `git clone https://github.com/rbertram90/HamletCMS-project.git my-project`
2. Remove the .git folder and run `git init` to start your project repository
3. `composer install`
4. Create database (default name = hamlet)
5. Copy `/config/config_default.json` -> `/config/config.json`
6. Change database connection details in config.json
7. Change `environment.root_directory` and `environment.public_directory` in config.json to reflect your file system
8. Run `php ./app/updatepublic.php` to copy accross required Hamlet files into your public directory - this will overwrite both `index.php` and `.htaccess` files if they already exist
9. Navigate to the site - you should be redirected to /cms/install
10. Complete the install form
11. Check everything is working, if not raise a <a href="https://github.com/rbertram90/HamletCMS/issues">Github issue</a> with details!
