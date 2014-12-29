<?php /*<html><head><title>501 Not Implemented</title></head><body><h1>501 Not Implemented</h1></body></html><!--*/
if (!defined('ADDIAH')) header('Location: index.php') && die;

/****************************************************************************\
 * Addiah php site framework configuration
\****************************************************************************/

date_default_timezone_set('Asia/Hong_Kong');

$config['debug'] = true;
$config['cache_lib']['enabled'] = false;

/*** Database access settings ***/
$config['db_server']= 'localhost';  // Database server
$config['db_user'] =  'root';       // Database username
$config['db_pass'] =  ''; // Database Password
$config['db_name'] =  'addiah';    // Database name
$config['table_prefix'] = 'pre_';  // Databast table prefix, if any

$config['controller'] = array (
   'lib' => array (
      'db_mysql',    // MS SQL database module
      'db-common',    // Common database module providing higher level functions
   ),
);

/*--><!--*/ ?>
