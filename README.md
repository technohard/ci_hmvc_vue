# CI HMVC VUE Bootstrap 4 WEBPACK 

> Codeigniter 3.1.6 HMVC + Vue 2 + Webpack + Bootstrap 4 Starter Template 

``` bash
# version 1.0.5
# default database using sqlite

```

## Requirements

- install composer
- install nodejs


## Build Setup

``` bash
on your project directory

# install composer dependencies
composer install

# install npm dependencies
npm install

#setup proxy for hot reload in webpack config  based on your backend localhost server
example : 
your php server running on localhost:8080
your proxy hot reload running on localhost:3000

# build for production with minification & browser hot reload
webpack --watch

# open your browser address with xampp running on your pc 
http://localhost:3000/ci_hmvc_vue

```
## Troubleshoot

``` bash

error unable install node-sass permission denied 

# from shell command prompt type in your project directory
npm install --unsafe-perm -g node-sass


```



For detailed explanation on how things work, consult maizier.b@gmail.com.
