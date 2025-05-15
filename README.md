# Instalación versión 7.4 de PHP a Ubuntu 24.04 y instalación de Owncloud

# Instalación versión 7.4 de PHP a Ubuntu 24.04

## Lo primero que tendremos que hacer es instalar la versión 7.4 de PHP a Ubuntu 24.04 para que podamos acceder a Onwcloud cuando lo tengamos instalado.

### 1. Primero tenemos que instalar los requisitos previos de PPA
   
![Captura de pantalla de 2025-05-14 12-25-17](https://github.com/user-attachments/assets/ff5d8138-a3d4-44f8-8fcc-0ccb8538aaa7)

### 2. Instalamos las herramientas necesarias para trabajar con los arxivos de paquete personal (PPA)

![Captura de pantalla de 2025-05-14 12-25-34](https://github.com/user-attachments/assets/bfe6b68f-b4ce-4124-b041-ff5fd25c2701)

### 3. Actualiza los repositorios

![Captura de pantalla de 2025-05-14 12-26-03](https://github.com/user-attachments/assets/fedebae0-fe74-4ca9-bad5-354a10efdd3a)

### 4. Instala las librerias de PHP de la versión 7.4

![Captura de pantalla de 2025-05-14 12-26-17](https://github.com/user-attachments/assets/16b6317e-039c-4f73-b26d-4b8927771b69)

![Captura de pantalla de 2025-05-14 12-26-40](https://github.com/user-attachments/assets/e7a80527-1afc-421c-a520-6cf5d346bbb0)

![Captura de pantalla de 2025-05-14 12-28-00](https://github.com/user-attachments/assets/e94725bf-61e7-4c74-9638-456c06595dca)

### 5.Seleccionamos de version de PHP que queremos

![Captura de pantalla de 2025-05-14 12-28-14](https://github.com/user-attachments/assets/9742a2da-e450-4efc-a6ea-ccb20f4cfb78)

### 6.Activamoslos modulos de apache2 necesarios

![Captura de pantalla de 2025-05-14 12-28-52](https://github.com/user-attachments/assets/60d6143d-e87b-4f68-80b8-db16e0d69d44)

![Captura de pantalla de 2025-05-14 12-29-18](https://github.com/user-attachments/assets/841331c6-51cd-4711-ad92-09878b346d16)

### 7. Reiniciamos Apache2

![Captura de pantalla de 2025-05-14 12-30-25](https://github.com/user-attachments/assets/dfc87327-076c-4747-beee-01f901c8f1ed)

### *Una vez hecho estos pasos ya tenemos instalada la versión 7.4 de PHP a Ubunutu 24.04*

# Instalación Owncloud

## 1. Lo primero que tenemos que hacer es bajarnos el arxivo zip de Owncloud y cambiarle el nombre a app-web.

![Captura de pantalla de 2025-05-14 11-56-06](https://github.com/user-attachments/assets/614fb9a4-6bac-4249-9d28-ef8dc959cb0d)

### 1. Actualizamos la maquina

![Captura de pantalla de 2025-05-14 11-56-58](https://github.com/user-attachments/assets/f1e9a8fb-8908-4650-9c97-cfdd7afbbe19)

![Captura de pantalla de 2025-05-14 11-57-24](https://github.com/user-attachments/assets/47f225c8-0bb3-44e2-80a3-fa1f79eeb297)

### 2. Instalamos el servidor web apache2

![Captura de pantalla de 2025-05-14 11-57-33](https://github.com/user-attachments/assets/eade8d86-f1f9-4dac-a89b-533105b44c2b)

### 3. Instalamos el servidor de base dee datos MYSQL-SERVER

![Captura de pantalla de 2025-05-14 11-57-46](https://github.com/user-attachments/assets/19685d25-9329-4d27-a658-fcea5f88d923)

### 4. Instalamos libreries de PHP

![Captura de pantalla de 2025-05-14 12-02-53](https://github.com/user-attachments/assets/b76d6156-f784-4d5d-bfcb-1e55887f0888)

### 5. Reiniciamos el servidor apache2

![Captura de pantalla de 2025-05-14 12-03-16](https://github.com/user-attachments/assets/095bab89-d921-4753-91d8-133844558d40)

# Creamos un usuario para poder acceder a la maquina remota
# Creamos un usuario y una contraseña 

![Captura de pantalla de 2025-05-14 12-03-49](https://github.com/user-attachments/assets/63d8ab4f-9fed-42db-9e88-1883a294a608)

## Damos privilegios al usuario que accedera a la maquina remota 

![Captura de pantalla de 2025-05-14 12-04-42](https://github.com/user-attachments/assets/77f57d7b-0971-4d31-9a5a-c575ced8b739)

![Captura de pantalla de 2025-05-14 12-05-07](https://github.com/user-attachments/assets/463b8127-a509-4568-8963-884bdd7af535)

# Descargamos los ficheros de la pagina web

### Si hemos cambiado el nombre de el arxivo zip que hemos descargado al principio tendremos que poner esto teniendo en cuenta que quiza donde tienes el arxivo zip no sea Baixades y sea Descargas

![Captura de pantalla de 2025-05-14 12-05-35](https://github.com/user-attachments/assets/86ed9137-a3c6-4568-85a8-5526a2507a0a)

### Vamos al directorio /var/www/html

![Captura de pantalla de 2025-05-14 12-06-59](https://github.com/user-attachments/assets/18b54821-c852-417a-a1fd-7a8c0fc44001)

![Captura de pantalla de 2025-05-14 12-10-08](https://github.com/user-attachments/assets/6cb4214b-e22f-406c-930c-0c81fa6f44e5)

### Descomprimimos el fichero que hemos descargado

![Captura de pantalla de 2025-05-14 12-10-33](https://github.com/user-attachments/assets/8b1e1d61-34fa-4190-9f4b-aa6f376f2de8)

### Copiamos los ficheros en la carpeta /var/www/html

![Captura de pantalla de 2025-05-14 12-11-57](https://github.com/user-attachments/assets/30902893-0cb3-4574-9056-c5358eb79704)

### Eliminamos la carpeta creada cuando hemos hecho unzip

![Captura de pantalla de 2025-05-14 12-12-20](https://github.com/user-attachments/assets/a38ad2a1-9736-4676-921e-444bbfbf36f9)

# Aplicacion de permisos

![Captura de pantalla de 2025-05-14 12-16-50](https://github.com/user-attachments/assets/2e10f142-7207-44de-be28-fcdf3c2f5cbe)

![Captura de pantalla de 2025-05-14 12-17-50](https://github.com/user-attachments/assets/fb8f4155-9186-49f5-80d9-b6eb9adab3cc)

![Captura de pantalla de 2025-05-14 12-18-30](https://github.com/user-attachments/assets/50a5580c-7c82-4756-8dd1-8ec9f31abcd1)

## Si hemos hecho todo podemos acceder a owncloud y poner los siguientes 

# usuari: usuario
# contrasenya: password
# base de dades: bbdd
# domini: localhost


![Captura de pantalla de 2025-05-14 12-46-03](https://github.com/user-attachments/assets/31ae447b-8d4f-403b-af82-f700784ff72e)

## Si hemos seguido todos estos pasos ya estaremos dentro de Owncloud y podremos configurarlo como queramos

![Captura de pantalla de 2025-05-14 12-46-25](https://github.com/user-attachments/assets/2ddbb004-1a69-4618-8d5b-6b6eb5976194)
