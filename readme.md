## Laravel API Boilerplate (JWT Edition)

Laravel API Boilerplate is a "starter kit" you can use to build your first API in seconds. As you can easily imagine, it is built on top of the awesome Laravel Framework. This version is built on Laravel 5.4!

It is built on top of two big guys:

* Dingo API - [dingo/api](https://github.com/dingo/api)
* Laravel-CORS [barryvdh/laravel-cors](http://github.com/barryvdh/laravel-cors)

What I made is an integration of these three packages and a setup of some authentication and credentials recovery methods.

## Installation

1. run `composer create-project francescomalatesta/laravel-api-boilerplate-jwt myNextProject`;
2. have a coffee, nothing to do here;

Once the project creation procedure will be completed, run the `php artisan migrate` command to install the required tables.


## Cross Origin Resource Sharing

If you want to enable CORS for a specific route or routes group, you just have to use the _cors_ middleware on them.

Thanks to the _barryvdh/laravel-cors_ package, you can handle CORS easily. Just check <a href="https://github.com/barryvdh/laravel-cors" target="_blank">the docs at this page</a> for more info.

## Feedback

I currently made this project for personal purposes. I decided to share it here to help anyone with the same needs. If you have any feedback to improve it, feel free to make a suggestion, or open a PR!
