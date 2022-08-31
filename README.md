# STEPS

`git clone git@github.com:AndreKravitz/unicont.com.git`

`ddev start`

`ddev composer install`

# Agregar codigo a drupal/web/sites/default/settings.php

`$settings['config_sync_directory'] = '../config/sync';`

# If you do not have the database set uuid value

`ddev drush config-set system.site uuid 3f7a3472-4767-47f8-8b01-9eca589c1502`

# Luego importamos

`ddev drush cim`
