# AngelZemm

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://angelgarciaco.com)

AngelZemm it's an example for passing data from a form to another keeping data between each step, applying Ajax by inside.. saving in a content entity.

  - You can see using Ajax behavior
  - You can see using Ajax Commands behavior
  - You can see using transactions between steps for recording data finally in a content entity

## Dependencies!

  - From Drupal: None.. just Drupal Core. 
  - It was developed under PHP 7.1.32 (This is for site Drupal 8).
  - It's required Composer.

### Installation

  - This module has been created under recommended project Drupal 8 (Drupal Version 8.8.6 - May 29 2020) with security update.
  - This Drupal version was installed with help of Composer.
  - This module was generated by drupal console.

#### Installing Drupal Site

So, according words above, follow this:

```sh
$ composer create-project drupal/recommended-project d8zemsite.com
$ cd d8zemsite.com
$ composer require drupal/console
$ drupal site:install
```

#### Installing Module AngelZemm (angelzemm)
This module can be located in modules directory.
```sh
$ cd d8zemsite.com
$ cd web/modules
$ mkdir custom
$ cd custom
$ git clone git@github.com:angarciaco/angelzemm.git
```

Finally, in extend administrative form of Drupal (d8zemsite.com/admin/modules), you can see module to install.

### Links

  - Public path for step by step form ( d8zemsite.com/angelzemm/multistep-one )
  - Page help ( d8zemsite.com/admin/help/angelzemm )
  - List of saved records ( d8zemsite.com/admin/structure/enangelzemm )

### Notes

  - Module includes a help page that contains links fot watching data saved.
  - Content Entity was generated with Drupal console and it is not required create it as Content Type inside Drupal.
  - Module creates this tables for the Content Entity:
  -- enangelzemm
  -- enangelzemm_field_data

### Host

May be you need to do this:

```sh
$ sudo nano /etc/hosts
127.0.0.1 d8zemsite.com
```

### Virtual Host

Drupal site was installed with MAMP and the settings used next:

```sh
<VirtualHost *:80>
    ServerAdmin webmaster@d8zemsite.com

    DocumentRoot "/Applications/MAMP/htdocs/d8zemsite.com/web"
    ServerName d8test.com

    DirectoryIndex index.php

    RewriteEngine On
    RewriteOptions inherit

    ErrorLog "/Applications/MAMP/logs/d8zemsite.com-error_log"
    CustomLog "/Applications/MAMP/logs/d8zemsite.com-access_log" common

    <Directory /Applications/MAMP/htdocs/d8zemsite.com/web/>
      Options Indexes FollowSymLinks Includes ExecCGI
      AllowOverride All
      Order deny,allow
      Allow from all
    </Directory>

</VirtualHost>
```

Finally, you need restart the web server (Apache in this case).


| Account | Link |
| ------ | ------ |
| Facebook | https://www.facebook.com/angelgarciacol |
| Twitter | https://twitter.com/AngelGarciaCO |
| LinkedIn | https://www.linkedin.com/in/angelgarciaco |
| Instagram | https://www.instagram.com/angelgarciaco |
| YouTube | https://www.youtube.com/channel/UCUUZM2FRvFOiP7j2b-psJug |
| WebSite | https://angelgarciaco.com |


By @angarciaco

