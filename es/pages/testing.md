# Notas sobre el testing de software

## Principios del testing

* Muestra la presencia de defectos
* El testing exhaustivo es imposible
* Realizar testing en una etapa temprana
* Es dependiente del contexto
* Falacia de la ausencia de errores luego del testing.

## Tipos de testing (algunos)

### Funcional

* Unit testing
* Integration Testing
* Smoke / Sanity

### No Funcionales

* Performance
* Escalabilidad
* Usabilidad

### Mantenimiento

* Regression
* Maintenance

### Sanity/Smoke
Utilizado para hacer un diagnostico rapido del sistema sin esperar a ejecutar la pruebas de aceptacion. Es decir toquetear un poco la interfaz simulando los casos clasicos de uso.

### Regression
Utilizado para hacer un tracking del error. Es decir, una vez que el error es detectado regresar hacia atraz para localizar la fuente del error.


## Automated testing

### Unit test
Se prueba el componente de una manera aislada

### Integration test
Se prueba el componente junto con el template

### Clean code practices
 * Menos de 10 lineas por metodo
 * Cada metodo realiza una sola tarea
 * El nombre del metodo es apropiado para la funcion que realiza
 * Dejar una linea entre las cada parte del patron de testing (las tres A)

### Patron en testing
 * Triple A: Arrange, Act, Assert

### Arrange
Prepara el escenario para el testing (inicializacion de variables)

### Act
Ejecucion de metodos que pueden modificar las variables

### Assert
Ejecucion de testing para comprobar el funcionamiento esperado de ACT.

### Set Up
Funcion utilizada en testing para inicializar el escenario de prueba. En Jasmine recibe el nombre de beforeEach().

### Tear Down
Funcion utilizada en testing para limpiar el escenario de prueba. En Jasmine recibe el nombre de afterEach().
