# Diseño y definición de tablas (Base De Datos)
Diagrama de base de datos realizado en MySQL Workbench

Escenario 1 - Playground
Queremos tener usuarios, los usuarios tendrán nombre, apellido, email, contraseña y categoría. Los usuarios podrán tener categoría de estudiantes, docentes, editores o
administradores. 
Lo siguiente que queremos es poder almacenar los cursos, que tendrán un título, una descripción, una imagen, una fecha de inicio, una fecha de finalización y un cupo máximo.
Los cursos tendrán unidades (para organizar el contenido) que tendrán un título, una descripción y una fecha de inicio.
Los usuarios (de cualquier tipo) podrán estar asociados a cursos.

Las unidades contendrán clases que también tendrán un título, una descripción, una fecha de inicio, y una marca de visibilidad (si el bloque está visible o no).
Las clases contendrán bloques. Los bloques tendrán un título y una marca de visibilidad.
Los bloques podrán ser de diferente tipo: texto, video, presentación, PDF o archivo. Los bloques también tendrán que poder guardar el contenido, sea texto o una URL, en caso de que el tipo sea video, presentación, PDF o archivo.

![Escenario 1 - Playground](https://user-images.githubusercontent.com/85651952/141163200-2d995ff6-660f-4888-be2d-e788ede1ca7c.png)

--
Escenario 2 - Bazar Digital
En charlas con los dueños entendemos que el bazar va a vender vajilla, juguetes y artículos de jardín, y van a tener empleados comunes, un coordinador, empleados de mostrador y repositores.
Todos los artículos tendrán nombre, precio, descripción, stock y aclararán si son para uso profesional o no.
Todos los empleados tendrán nombre, apellido, dni, sueldo y un rol.

Los empleados de mostrador son los únicos que podrán cobrar y tendrán una caja donde guardar lo que cobran, y los repositores podrán ir a la bodega de almacenamiento. Para eso esperamos poder saber cuántos productos están exhibidos y/o en el depósito.
Los empleados pueden vender un artículo generando una comisión adicional del 10% del valor del artículo. Para las ventas esperamos poder almacenar fecha, artículos, medio de pago y total de la compra.

![Escenario 2 - Bazar Digital](https://user-images.githubusercontent.com/85651952/141163340-30ff733e-2642-487e-8dcb-e6cbe8e1e93b.png)
