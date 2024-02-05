# HeroDevs Drupal Demo Site

For additional reference, see the Google Doc:
HeroDevs—Working with Drupal
https://docs.google.com/document/d/1GuESxufOfUWEt_Da_ZrmUutdnX2oCdIFkMhKgHW7WB4

## Local Installation
1. Install Lando (https://lando.dev/download).
2. Clone this repo.
3. In the project directory, initiate the containers with:

   `lando start`

4. Install Drupal with:

   `lando drush site:install --db-url=mysql://drupal7:drupal7@database/drupal7 -y`

5. Change the site name:

   `lando drush vset site_name "HeroDevs Drupal 7 Demo Site"`

6. Change the password:

   `lando drush upwd admin --password="password"`

7. Visit the URL:

    `http://hd-drupal-7.lndo.site`



