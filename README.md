#  likec4_training

Proyecto que uso para formarme en Like C4

## Top-level statements

 - **specification** -> define los tipos de elementos que se van a usar en el modelo, como **system**, **app**, **microserve**...
 - **model** -> elementos de la arquitectura, jerarquía, composición y relaciones.
 - **views** -> vistas.
 - **global** -> predicados compartidos globalmente.

## Specification

[Explicación oficial del bloque](https://likec4.dev/dsl/specification/)

En este bloque de datos definimos la notación que vamos a usar.

### Tipos de elementos

Con `element` se define el tipo que se puede usar en todo el modelo.

    specification {
    
      // Define whatever you want
      element user
      element cloud
      element system
      element application
      element component
      element controller
      element microservice
      element queue
      element restapi
      element graphqlMutation
      element repository
      element database
      element pgTable
    }

