## Prerequisites
* MacOS
* PHP >= 7.0.0
* composer

## Install PHP & compser
```
brew update
brew search php
brew install php
```

### Install Laravel with Composer
```
$ composer global require "laravel/installer" 
```

### path setting
```
$ vi ~/.bash_profile  
// add line 
export PATH=~/.composer/vendor/bin:$PATH
$ source ~/.bash_profile  
```

### Creat Laravel Application AND Start the server
```
$ laravel new demo_laravel
$ cd demo_laravel
$ php artisan serv 
```

### Access
http://127.0.0.1:8000 on your browser.
