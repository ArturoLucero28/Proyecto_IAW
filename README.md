# Proyecto PHP MVC

Este proyecto consiste en una aplicación web desarrollada en PHP utilizando el patrón de diseño MVC. La aplicación proporciona funcionalidades como la gestión de productos, inicio de sesión para usuarios y administradores, y un carrito de compras.

## Funcionalidades implementadas

- **Listado de productos**: Permite ver todos los productos disponibles en la tienda.(Funcion a poder ver por todos)
- **Listado de usuarios**: Permite ver todos los usuarios del sistema.(Funcion a poder ver por administradores)
- **Ver un producto**: Muestra detalles específicos de un producto, como su descripción, imagen y precio.(Si no está la sesion iniciada mostrará un enlace para iniciar sesion, si es administrador de borrar producto y si es usuario la función será de añadir al carrito)
- **Inicio de sesión**: Los usuarios pueden iniciar sesión .(Funcion a poder ver por todos que no esté iniciado)
- **Dar de alta nuevo producto**: Solo los administradores tienen permiso para agregar nuevos productos al sistema.
- **Dar de alta nuevo usuario**: Solo los administradores tienen permiso para agregar nuevos usuarios al sistema.(en proceso...)
- **Añadir producto al carro de compra**: Los usuarios pueden agregar productos al carro de compras mientras navegan por la tienda.(Funcion solo para los usuarios)
- **Ver carro de la compra**: Permite a los usuarios visualizar los productos que han añadido al carro de la compra.(Funcion solo para los usuarios)
- **Quitar producto del carro de la compra**: Permite a los usuarios eliminar los productos que han añadido al carro de la compra.(Funcion solo para los usuarios)
- **Borrar producto**:Solo los administradores tienen permiso para eliminar los productos del sistema

## Tecnologías utilizadas

- PHP
- HTML
- CSS
- MySQL

## Patrón de diseño MVC

El proyecto sigue el patrón Modelo-Vista-Controlador (MVC) para separar la lógica de negocio de la presentación y la interacción con la base de datos.
![image](https://github.com/ArturoLucero28/Proyecto_IAW/assets/146435794/8dea994d-685f-45ab-b40f-3be76ebc5096)
![image](https://github.com/ArturoLucero28/Proyecto_IAW/assets/146435794/cc858ec6-2d21-436b-8e86-5f03403af437)

## Detalles a concretar
El header se debe aplicar dos veces, es decir si iniciamos sesion tenemos que volver a darlea listar productos o recargar la pagina o realizar cualquier interaccion para recargar el header, al cerrar sesion realizamos cualquier interaccion o mejor recargar para actualizar su interfaz.
