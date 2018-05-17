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


## Angular Testing 

### Links de interes

* [Codecraft](https://codecraft.tv/courses/angular/unit-testing/jasmine-and-karma/) *Resumen de testing en angular*

* [Angular Testing Docs](https://angular.io/guide/testing) *Documentacion oficial de la pagina de Angular*

### Jasmine
Es un framework enfocado en BDD para testing en JavaScript
