README - FILESYSTEM


INSTALLATION
------------
Make sure Composer is downloaded and installed. You can reference the instructions below or the official composer documentation https://getcomposer.org/download/

```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');" 
```

You have the option of placing the Composer PHAR as part your `PATH`, so you can access it globally. 

```
mv composer.phar /usr/local/bin/composer # or whatever path you want
```
Now you can run composer by typing `composer` instead of `php composer.phar`

I created the symfony project by running this command: 
```
composer create-project symfony/skeleton FileSystem
```

Run the application:
    1. Change to the project directory `FileSystem`
    2. Create your code repository with the git init command
    3. Execute the php -S 127.0.0.1:8000 -t public command
    4. Browse to the http://localhost:8000/ URL.

       Quit the server with CTRL-C.
       Run composer require server --dev for a better web server.

  * Read the documentation at https://symfony.com/doc



Documentation
-------------







About ME
--------
