This angular.js repository has [30 seconds+ of latency due to the livereload.js?snipver=1 failing to load problem](http://stackoverflow.com/q/21897385/3290121).

This repository was created following everything on the [Yeoman's guide](http://yeoman.io/). Namely:

* `npm install -g yo`
* `npm install -g generator-webapp`
* `npm install -g generator-angular`
* `yo angular`
* `bower install angular-ui`
* Changed the hostname in Gruntfile.js from `localhost` to `0.0.0.0`
* `grunt test` 
* `grunt serve`

What did I do wrong? How can I fix it?
