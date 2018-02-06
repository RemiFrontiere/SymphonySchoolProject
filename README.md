SchoolSymfony
==============

## Usefull link
https://symfony.com/

Components : https://github.com/symfony/symfony

Form themes :  https://symfony.com/doc/current/form/form_themes.html


## Install dependencies
>composer install
or
>php composer.phar install

## Start
>bin/console server:run

## Get environment variable available for this bundle
>bin/console config:dump-reference [NomBundle] (sans Bundle)

### Exemple:
>bin/console config:dump-reference framework

>bin/console config:dump-reference webserver

## Database has been created ?
>bin/console doctrine:database/create




## Doctrine DB
    /**
     * @ORM\Id                      --> For PRIMARY KEY
     * @ORM\GeneratedValue          --> Auto-Generated Value
     * @ORM\Column(type="integer")  --> Column type -- Default(string)
     */
