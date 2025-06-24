# Portafolio_CRUD_API

### Este es un proyecto donde se implemento un CRUD junto con una API a un portafolio personal

## Tecnologias usadas
- Php
- Javascript
- Css
- Html

## Detalle de uso de IA

Se uso la IA "Deepseek" para ver el tema de organizacion de archivos del proyecto, rutas de los diferentes archivos

un ejemplo fue que le pedi que me ayudara, porque al subir una imagen cuando creaba un post, no me subia la imagen o me la subia pero no me detectaba el formato, por que lo que me sugirio verificar las rutas en el servidor de filezilla, y tambien el codigo con las rutas correctas y tambien los formatos que deberia admitir

Archivo: add.php
 $imagen = $_FILES['imagen']['name'];
  $tmp = $_FILES['imagen']['tmp_name'];
  move_uploaded_file($tmp, "uploads/$imagen");

## URL publica del proyecto
https://teclab.uct.cl/~leandro.diaz/portafolio_crud_api/public.view.php
