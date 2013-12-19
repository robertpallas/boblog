Ironman DB
##########

:date: 2013-12-19 17:30
:tags: personal projects, angular, laravel
:category: blog
:slug: ironman-db
:author: Robert Pallas
:summary: Ironman DB project written with AngularJS and Laravel.

`Ironman DB <http://edetabel.tri.ee/>`_ is a small app for tracking Estonians long distance triathlon results. Data is
added by the users so one of the main requirements was to make this process as intuitive and fast as possible. This was
achieved by using autocomplete fields, helpful data selectors and modern error handling. Filtering
data allows for amusing rankings to be displayed and the site challenges Estonian athletes to push themselves to beat times
their neighbours clocked last year. I released Ironman DB for Hawaii Ironman weekend in October 2013.

Tech stack
----------
* Angular JS - this project was the first time for me to use Angular and also the first to build an application that I
  would release to public with a full-blown Javascript framework under it. I did enjoy the experience and will most definitely be using
  Angular again. I also found it true that Angular is quite easy to get started but to use it to its full power you need some
  practise. Next time I would organize my code better from the get-go and take more advantage of directives. Directives are
  Angular way of extending HTML semantics with elements with custom behavior. They were a bit tricky to get started with because
  the whole concept was new to me but I saw their potential in code re-use and clean sources quite quickly. Only downside to
  the framework that I can think of is rather poor official documentation. This can be overcome with extensive online resources
  collection that is listed in `jmcunningham's Github repo <https://github.com/jmcunningham/AngularJS-Learning>`_.
* Laravel - I chose to use PHP for building light weight RESTful API for deployment reasons. Choice of Laravel was made to
  test out the new hotness in market of PHP MVC frameworks. This was also a new experience for me but a lot less demanding
  than using Angular because the API is simple with 1 endpoint and 3 methods, developing in Laravel is effortless
  and I have good background in writing apps on top of Codeigniter and Zend.
* MySQL - I already had the data from earlier version of the same application and with Laravels query builder being quite
  awesome the only real SQL queries I had to write was for building a view for getting athletes records displayed.
* Twitter Bootstrap - I chose to use a shortcut for design. Modifications to style sheets are minimal. To add some sharp
  interaction capabilities I added `AngularStrap <http://mgcrea.github.io/angular-strap/>`_.