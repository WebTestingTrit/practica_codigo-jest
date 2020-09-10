# Práctica pruebas de código con Jest

## Definición
Rehacer la práctica incial de las primeras pruebas

Implementar una pila Last-In-First-Out (LIFO) en JavaScript

Crear un estructura que permita agregar elementos. Al recuperar los elementos devolverá el último agregado. Al devolverlo lo eliminrá de la pila.

### Requerimientos

Se añadirán uno a uno con el método `push(item)`

Se recuperarán uno a uno con el método `pop()`

Pero esta vez se requiere:

  - Usar Jest para las pruebas

  - Partir de las pruebas antes del código. Es decir usar TDD.
  
#### Recomendaciones

Documentarlo siguiendo la técnica BDD

### Commits y deploy

- Se recomienda usar convenio de nombrado durante los commits.

- Documentación [standard-version](https://www.npmjs.com/package/standard-version) to produce a changelog file from [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/)

- Para subir los cambios usar el script `npm run deploy` Se encarga de hacer el push y crear un changeLog con lo hecho.

### Code style y Prettier

-  Recomendado [extension](https://github.com/prettier/prettier-vscode) for VSCode
