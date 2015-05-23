Charisma for Symfony
========================

This is just the base layout/template for Symfony 2.6 PHP (Charisma)
for your back admin webpages with most common regions extended.

1- Download the entire project and copy it  with carefully (merge App files if need it) into your new Symfony2 project

2- Setting up a virual host pointing to your Symfony/web/ folder (this is important to get assets works)

3- Configure your Symfony commons (configs,database,etc...)

4- Run the command: composer update

5- Run the command: php app/console assets:install

6- Now run your http://charisma.virtualhost/app_dev.php

(homepage must be set to AppBundle:DefaultController:index or another file extending app/Resources/views/base.html.twig)

-----
For download Symfony 2.6.* use composer command:

$ composer create-project symfony/framework-standard-edition path/ "2.6.*" or http://symfony.com/download


-----
Leave a comment, thanks

Original project: https://github.com/usmanhalalit/charisma

by @juliomatcom

