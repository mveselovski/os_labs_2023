# Лабораторна робота 2

## Завдання

 Використовуючи віртуальні машини з першої лабораторної роботи налаштувати наступні сервіси

   1. Вебсервер - Apache or Nginx (якщо ваше прізвище має парний номер в списку групи ставимо Apache, непарне - Nginx)
   2. База даних - mysql
   3. php - використовуємо php-fpm для обох варіантів веб серверів
   4. Придумуємо доменне імʼя типу mveselovski.local і прописуємо його в файлі hosts відповідно до вашої операційної системи

    ```text
    192.168.0.2 mveselovski.local   
    ```

   6. Перевіряємо що працює php заливши в /var/www/html файл phpinfo.php з наступним вмістом

    ```php
    <?php
    phpinfo();
    ?>
    ```

   7. Перевіряємо у вашому броузері що сервер налаштовано правильно <http://mveselovski.local/phpinfo.php>

   8. В папку /home/webroot завантажуємо Wordpress для парних номерів в списку групи, для непарних - OpenCart
   9. Створюємо VirtualHost для нашого сайту відповідно до вашого веб сервера.
   10. Завершуємо інсталляцію Wordpress/OpenCart
   11. Створюємо та налаштовуємо самопідписаний SSL сертифікат для нашого сайту
   12. Перевіряємо що сайт працює

## Матеріали які допоможуть вам виконати лабораторну роботу

- Apache - <https://httpd.apache.org/docs/>
- Nginx - <https://nginx.org/en/docs/>
- PHP - <https://www.php.net/manual/en/>
- Mysql - <https://dev.mysql.com/doc/>
- Wordpress - <https://wordpress.org/support/article/how-to-install-wordpress/>
- OpenCart - <https://docs.opencart.com/installation/>
- Self-signed SSL - <https://www.digitalocean.com/community/tutorials/how-to-create-a-self-signed-ssl-certificate-for-nginx-in-ubuntu-16-04>
