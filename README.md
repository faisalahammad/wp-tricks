#WORDPRESS TRICKS
##Awesome tricks about WordPress.

###Define Memory limit (Allocate More Memory)

	1. Edit your wp-config.php file and enter something like:

		define('WP_MEMORY_LIMIT', '256M');

	2. If you have access to your PHP.ini file, change the line in PHP.ini
	- If your line shows 64M try 256M:

		memory_limit = 256M ; Maximum amount of memory a script may consume (64MB)

	3. If you don’t have access to PHP.ini try adding this to an .htaccess file:

		php_value memory_limit 256M

	4. If none of the above works then talk to your host.