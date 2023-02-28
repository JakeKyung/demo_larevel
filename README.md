# Installation History Laravel on Mac

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

#### Access
http://127.0.0.1:8000 on your browser.


### valet install
* hosts 파일 설정 하지 않고 사용할 수 있음, 적은 메모리로 개발진행 가능
```
$ composer global require laravel/valet
$ valet install
// 라라벨 프로젝트 상위 경로에서 실행, 디렉토리 명으로 접근할 수 있다.
$ valet park
This directory has been added to Valet's paths.
```
#### Access
http://demo_laravel.test

