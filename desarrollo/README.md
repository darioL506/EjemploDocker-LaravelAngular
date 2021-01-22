Entorno Desarrollo:

Windows: <<C:\Windows\System32\drivers\etc>>
Ubuntu: <</etc/hosts>>

1º Modificar el archivo hosts y añadir las siguientes lineas:

127.0.0.1	bolsaTrabajo.com
127.0.0.1	phpmyadmin.com

2º ejecutar desde la consola en el directorio "desarrollo" el comando:

docker-compose up -d