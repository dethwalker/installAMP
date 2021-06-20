# installAMP
Install Apache, MariaDB, PHP and WordPress and configure them with a few clicks

WARNING!
The idea of this project is for me to learn bash scripting.
This code may not be ideal.
This code has only been tested on Fedora 33 Server.

What does this code do?

-Install Apache and configures it the way it is instructed here:
https://www.server-world.info/en/note?os=Fedora_33&p=httpd&f=1

-Install PHP for Apache the way it is instructed here:
https://www.server-world.info/en/note?os=Fedora_33&p=httpd&f=6

-Install MariaDB and configures it the way it is instructed here:
https://www.server-world.info/en/note?os=Fedora_33&p=mariadb&f=1

-Install WordPress and configres it (without the last part) the way it is instructed here:
https://fedoramagazine.org/howto-install-wordpress-fedora/#:~:text=%20How%20to%20install%20WordPress%20on%20Fedora%20,so%20the%20web%20server%20can%20perform...%20More%20

It takes input from the user for:

"ServerAdmin" in /etc/httpd/conf/httpd.conf
"ServerName" in /etc/httpd/conf/httpd.conf
WordPress database name
WP database username
WP database password

I am thinking of adding more stuff in the future but for now this is all.
Any suggestions are welcome.

