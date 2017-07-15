You must set your vhost config as following wor that to work 

Windows :

<VirtualHost *:80>
    ServerName localhost

    ServerAdmin webmaster@localhost
    DocumentRoot Path to laravel app home dir\public\admin-lte

    <Directory Path to laravel app home dir>
        Allow from All
    </Directory>

</VirtualHost>

</VirtualHost>

