CONTENTS OF THIS FILE
---------------------
 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Maintainers


INTRODUCTION
------------
The Migrate Cron module provides the functionality of executing the migrations
on cronjob at a particular interval. The module provides the UI as well, so each
migration cron interval can be set individually.


REQUIREMENTS
------------
This module depends on
    * migrate
    * migrate_plus


INSTALLATION
------------
* Install as you would usually install a contributed Drupal 8 module. See:
https://www.drupal.org/docs/8/extending-drupal-8/installing-drupal-8-mod...

* Using composer and drush

```composer require drupal/migrate_cron
drush en migrate_cron```


CONFIGURATION
-------------
After installation, set individual cron intervals by accessing
/admin/config/system/migrate-cron


MAINTAINERS
-----------

Current maintainers:
 * Vadim Malasevschi (vadimski) - https://www.drupal.org/u/vadimski
 * Bohdan Artemchuk (bohart) - https://www.drupal.org/u/bohart
