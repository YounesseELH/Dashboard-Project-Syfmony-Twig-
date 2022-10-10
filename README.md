# Steps :
1- git clone .. <br>
2- composer require symfony/web-server-bundle <br>
3- edit .env <br>
4- php bin/console doctrine:migrations:migrate (if you want remove my migrations then php bin/console make:migration then php bin/console doctrine:migrations:migrate)<br>
5- symfony server:start <br>
