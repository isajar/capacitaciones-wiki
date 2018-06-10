# Bootsrap 4 

## Grilla

* [Doc oficial grilla](https://getbootstrap.com/docs/4.0/layout/grid/) 

### Reglas de la grilla
 
 * El container es el contenedor principal, en el iran todas las filas y columnas. Con el container podemos centrar nuestra pagina 

 * Las filas (row) son grupos HORIZONTALES de columnas
 * Todo el contenido debe ir dentro de columnas (col) 
 * Y las columnas deben ir directamente dentro de las filas (row)

## Tamaños de columna

 * Los tamaños de Columna en Bootsrap 4 son:

    * `.col`        Extra Pequeño (Extra Small) **Smartphones Vertical** Menos de 544px
    * `.col-sm` 	Pequeño (Small) **Smartphones Vertical**	 		 Mas de 544px y Menos de 768px
    * `.col-md` 	Mediano (Medium) **Tablets** 						 Mas de 768px y Menos de 992px  
    * `.col-lg` 	Largo (Large) **Computadoras**						 Mas de 992px y Menos  1200px
    * `.col-xl` 	Extra Largo (Extra Large) **Computadoras**			 Mas de 1200px

## Utilities

* Bootstrap provides some handful helper classes, for faster mobile-friendly development. These can be used for showing and hiding content by device via media query, combined with large, small, and medium devices.
* Son propiedades que se colocan en los tags
* [Documentacion oficial](https://getbootstrap.com/docs/4.0/utilities/)


## Flex 

* Util para manejar la alineacion de las columnas
* [Doc oficial flex-box](https://getbootstrap.com/docs/4.0/utilities/flex/)

### Reglas

* Utilizar disposicion normal de grilla: contenedor->fila->columna
* Crear una clase padre que utilice la clase `d-flex`
* Luego todos los `<div>` hijos se podrán manipular con flex-box.

### Ejemplos
* [Ejemplo en html](flexbox.html)
* [Ejemplo 2 en html](flexbox2.html)
* [Ejemplo 3 en html](flexbox3.html)


## Spacing utilities (margin and padding)

* Sirve para dar espaciado tanto de margenes como de padding
* [Documentacion oficial spacing](https://getbootstrap.com/docs/4.0/utilities/spacing/)

## Borders 

* Util para seleccionar los bordes que queremos que se muestren
* [Documentacion oficial borders](https://getbootstrap.com/docs/4.0/utilities/borders/)


## Tipografia 

* Aca se define los h1,h2, etc del texto manejado por bootstrap
* [Doc oficial tipografia](https://getbootstrap.com/docs/4.0/content/typography/)

## Imagenes 

* Clases para manejar imagenes de forma responsiva
* [Sitio gratuio para traer imagenes recortadas](https://picsum.photos/200/200) **image placeholder services**
* [Documentacion oficial imagenes responsivas](https://getbootstrap.com/docs/4.0/content/images/)
