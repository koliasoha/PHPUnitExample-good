Install Instructions

1.  Clone
2.  Composer install
3.  Run Tests on windows:

 vendor\bin\phpunit --bootstrap vendor\autoload.php tests\EmailTest

mac: 
 vendor/bin/phpunit --bootstrap vendor/autoload.php tests/EmailTest

1, Install the Visual C++ Redistributable for Visual Studio 2015.
After that download PHP for Windows.

2, Expand the zip file into the path C:\PHP7

3, In the PHP7 folder rename the file php.ini-development to php.ini

Change the memory limit from 128M to 1G

Uncomment the following lines by removing the ; 
; extension_dir = "ext"
extension=php_gd2.dll
extension=php_curl.dll
extension=php_mbstring.dll
extension=php_openssl.dll
extension=php_pdo_mysql.dll
extension=php_pdo_sqlite.dll
extension=php_sockets.dll

4, Add C:\PHP7 to your Windows system path.
Open System Control->Advanced System Settings->Environmental Variables
Click on the path row under 'System variables' and click edit 
Click 'new' and add the row C:\PHP7
Click OK and close the System Control Panel.

5, Check to verify that PHP is working.
In a terminal window type php -v. It should respond with the version of PHP.

6, Install composer.
Download the Windows Installer for Composer and run it.

7, Verify that the composer is working.
Run the command composer in the terminal.

PHP and PHP Composer are now installed.

7, Clone the git repository PHPUnitExample.
Copy the link from the git repository PHPUnitExample then go to PHPStorm VCS| Checkout from Version Control| Git.
In the window paste the link and click clone.

8, In order to test the code use the command from the readme.md file.   