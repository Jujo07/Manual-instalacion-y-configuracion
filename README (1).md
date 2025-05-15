# Configuración de MYSQL

## Accedemos a la consola de Mysql
### Desde un terminal siendo root ponemos esto:

![Captura de pantalla de 2025-05-14 12-03-49](https://github.com/user-attachments/assets/c52d98d2-debe-4ea1-bc68-08862a95cccd)

## Una vez hecho esto ya tendriamos que estar denttro de la consola de Mysql

![Captura de pantalla de 2025-05-14 12-07-17](https://github.com/user-attachments/assets/a91db0bf-e259-4bf5-95a1-cc36c6696461)

## Creación de la base de datos
### Dentro de la consola ejecutamos los siguientes comandos para crear una base de datos la cual tendra el nombre bbdd

![Captura de pantalla de 2025-05-14 12-07-40](https://github.com/user-attachments/assets/7a4fe2e5-58a3-497a-b0a3-e4b9790aaa92)

## Creación de un usuario

![Captura de pantalla de 2025-05-14 12-08-03](https://github.com/user-attachments/assets/6a81f26b-f222-4af7-9cb3-9cf5a0a19b25)

## A continuación damos privilegios al usuario

![Captura de pantalla de 2025-05-14 12-08-10](https://github.com/user-attachments/assets/111bd711-b4ab-4e63-a1bd-d183808830bf)

## Salimos de la base de datos

![Captura de pantalla de 2025-05-14 12-08-52](https://github.com/user-attachments/assets/2856ac76-ff5e-4a3d-8fb0-d04141471888)

## Creación de un usuario para acceder desde una maquina remota

![Captura de pantalla de 2025-05-14 12-55-14](https://github.com/user-attachments/assets/b9454d85-ab23-4d4a-9ae9-801c3ac2f05c)

# Configuración de Owncloud

# 1. Creación de usuarios

## Para crear usuarios tendremos que ir a nuestro nombre de usuario arriba a la derecha y seleccionar el apartado que pone users

![Captura de pantalla de 2025-05-15 11-59-43](https://github.com/user-attachments/assets/c06949af-4b18-4d60-8557-142311a8e6c7)

## Una vez dentro de este apartado tendremos que darle a la opción de añadir grupo, esta opción esta en la esquina superior izquierda

![Captura de pantalla de 2025-05-15 12-01-07](https://github.com/user-attachments/assets/346ef595-2c4b-447a-be22-020764f5dd3d)

## Crearemos 2 grupos, el grupo editores y el grupo de lectores ya que el grupo de admins ya estara creado ya que nosotros somos uno

![Captura de pantalla de 2025-05-15 12-07-51](https://github.com/user-attachments/assets/872d689c-dac5-4b60-a392-1a7e7b086d05)

## Para crear usuarios tendremos que poner el nombre que tendra, el correo y tendremos que seleccionar en el grupo que queremos que esten ellos según los permisos que les queramos dar

![Captura de pantalla de 2025-05-15 12-09-26](https://github.com/user-attachments/assets/a1485d6f-e958-4809-bb85-f2839fc9ade2)

## Yo he creado un Admin, un editor y un lector por lo tanto los grupos que he creado se ven asi:

![Captura de pantalla de 2025-05-15 12-09-57](https://github.com/user-attachments/assets/673eb59b-753a-471a-a10c-c9bd08626c5f)

# 2 Asignación de roles y permisos

## Vamos a una carpeta que queramos compartir y le damos a la opción de compartir. 
## Una vez dentro odremos añadir a los usuarios que queramos simplemente escribiendo su nombre en el buscador y seleccionandolos

![Captura de pantalla de 2025-05-15 12-12-00](https://github.com/user-attachments/assets/b7b0ebb1-f42c-49c3-94b4-c05ea2bd6caf)

## Tambien añadimos los grupos que hemos creado anteriormente

![Captura de pantalla de 2025-05-15 12-12-48](https://github.com/user-attachments/assets/3d1d3048-3fb1-4a34-a37e-c7f589bcbaea)
![Captura de pantalla de 2025-05-15 12-16-08](https://github.com/user-attachments/assets/86e07c37-5dc8-4f8b-a1de-4f5b0a48778d)

## Una vez añadidos los usuarios y lo grupos, damos los permisos que queramos a cada uno

![Captura de pantalla de 2025-05-15 12-18-46](https://github.com/user-attachments/assets/67808b35-406c-48d9-a23d-6cb997eb4aae)

# 3. Administración de archivos

## Podemos crear archivos y carpetas simplemente yando a Files y seleccionando la opcion de añadir que es la que tiene el simbolo +

![Captura de pantalla de 2025-05-15 12-24-59](https://github.com/user-attachments/assets/18e89048-e903-40d7-9464-abe215a78c94)

## Si queremos compartirlo con gente y cambiar las politicas de seguridad tenemos que ir a compartir el archivo que queramos y le damos a crear un link público, una vez hagamos esto nos saldran un tipo de opciones las cuales podemos modificar como: la fecha de caducidad, la contraseña para entrar y los permisos que tendran los usuarios que entren en el link

![Captura de pantalla de 2025-05-15 12-25-38](https://github.com/user-attachments/assets/2e430707-cb97-48c8-983a-f2e4b3466efa)

![Captura de pantalla de 2025-05-15 12-25-47](https://github.com/user-attachments/assets/5fc70cba-3ac0-46a2-8200-2d61a99a0969)

# 4. Acceso desde una maquina cualquiera de la red

## El primer paso sera conseguir la Ip de nuestro Owncloud que es tan facil como ir a nuestra terminal y poner el comando: Ip a
## una vez tengamos la Ip ponemos esto en el buscador de otro dispositivo: http:NuestraIp/owncloud
## Hacemos login con una cuenta de usuario que hayamos creado y ya estaremos dentro

## Si no nos deja entrar tendremos que modificar el archivo de config/php dentro de la carpeta config, dentro de la carpeta Owncloud

![Captura de pantalla de 2025-05-15 13-08-44](https://github.com/user-attachments/assets/07d13a9e-e0cf-499b-a157-a7d7e516a2fa)
