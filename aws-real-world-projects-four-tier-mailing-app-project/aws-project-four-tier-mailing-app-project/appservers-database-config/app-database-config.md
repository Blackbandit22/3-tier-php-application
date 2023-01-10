## Create a Database config file in the application servers 
vi dbinfo.inc

## Copy and Past the Below Data in the file after updating
```bash
<?php

define('DB_SERVER', 'prod-php-app-db.cklz7mx3d0oa.us-east-2.rds.amazonaws.com');
define('DB_USERNAME', 'phpappadmin');
define('DB_PASSWORD', 'phpappadmin');
define('DB_DATABASE', 'phpappdatabase');

?>
```