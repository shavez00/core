# core
PHP Autoloader-use for lazy loading of undefined classes

This is simple lazy loading autoloader for PHP

This built-in function (autoload()) allows us to provide our own code,  to use as a means of loading a class based on the name of the class requested.  The pattern we will use to ﬁnd class ﬁles will be the title-case class name with a directory separator between each word and .php at the end. So if we need to load the Framework\Database\Driver\Mysql class, we will look for the ﬁle framework/database/driver/mysql.php (assuming our framework folder is in the PHP include)
	
$class = php class passed to autoload function to be included

1. Installation

Installation is simple.  Just copy this file into the root directory of your project.
Once the file is in the root directory of your project edit the script so that line 15 includes the path to the folder where your classes exist.  All files that contain your classes MUST use lowercase letters only for their file names.
