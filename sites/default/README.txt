Local connection info should be added to settings.local.php, and not settings.php.

An example connection array would look like:

-------------

<?php

$databases = array (
  'default' =>
  array (
    'default' =>
    array (
      'database' => 'kcdug',
      'username' => 'USER',
      'password' => 'PASS',
      'host' => 'localhost',
      'port' => '',
      'driver' => 'mysql',
      'prefix' => '',
    ),
  ),
);
