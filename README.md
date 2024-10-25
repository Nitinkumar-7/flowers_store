# flowers_store
php project 
Required phpmyadmin (add database in phpmyadmin) and xamp (run apache and MySQL server) if want to run without lando.

If run with Lando, need to setup lamp service and upload db on phpmyadmin .

example : 

recipe: wordpress
config:
  webroot: .
services:
  myservice:
    type: phpmyadmin
