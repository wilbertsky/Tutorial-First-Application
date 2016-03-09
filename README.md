# Slim Tutorial

This is a very simple Slim project to serve as an example application of using Slim 3 with Monolog, Phinx, PHP views and Composer to manage dependencies.  In order to use the application as it stands:

* run `php composer.phar install` to get the dependencies
* then run `php vendor/bin/phinx migrate` to get your database set up (the config is in `phinx.yml` so adjust as appropriate for your platform)

Patches to both tutorial and code are welcome.
