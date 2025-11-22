![image](./sample/Endgame%20screenshot.png)

Download xampp and start setup on your computer

Source setup:

open PHPMyAdmin

Create your a new database call it whatever you want

Navigate to the created database select Import tab

Browse and choose travian.sql file in the root directory then import the data

Create a config.php file in the root directory

copy and paste this in the config file

<?php
define("GAME_HOST", "localhost");
define("DB_USER", "root");
define("DB_PASS", "");
define("DB_NAME", "travian");
?>

replace the information with your prefer environment info

Enjoy the game!

Apache=2.4.43
PHP=7.3.17
MYSQL=5.2.3

Any bugs please report to Issues tab from this repository I'll investigate and fix If I could
