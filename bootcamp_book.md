
# Test Camp (Core)

Test Camp es un encuentro quincenal diseñado para brindar apoyo y guía a las estudiantes que se encuentran  en los primeros 3 proyectos de bootcamp para que ellas logren alcanzar los objetivos de aprendizaje relacionados a testing. En este espacio, nos reunimos para abordar dudas, ver estrategias de creación de test y compartir información relacionada con las herramientas de testing. La sesión es liderada por coaches quienes compartirán feedback sobre buenas prácticas así como recomendaciones para que las estudiantes puedan abordar los test en la etapa core de bootcamp. Como resultado se espera cultivar las habilidades en las estudiantes y maximizar su aprovechamiento de estas técnicas fundamentales en el desarrollo de software.

## Sesión de activación

El espacio de activación tiene como objetivo transmitir la importancia de hacer testing en sus proyectos y comunicarles cómo es la dinámica que se lleva a cabo en test camp así como la invitación al espacio. Podemos apoyarnos de las siguientes slides: [Link a las slides](https://docs.google.com/presentation/d/1Mvd8exSN7EmAg7Oi7xSL7xAEQJh98oJtBhnlnpQTAAU/edit?usp=sharing)

### Consideraciones en la sesión de activación:

- Duración: 1h
- El ejercicio comienza a partir del ejemplo de la suma
- Acomodar, Actuar, Afirmar
- Suite + Test
- Aserción + Matcher

## Alineación como coaches

La importancia de los test en bootcamp:
- Permite tener un código mantenible
- Garantizar la calidad del código desde el principio.
- Prevenir errores antes de que el código vaya a producción.
- Facilitar la integración y despliegue continuo de forma segura.
- Ayuda a no tener código spaghetti

Qué aportan las pruebas en el código de las estudiantes:
- Verificación de que las funciones realizan lo que se espera de ellas (Validación de que el código cumple con los requisitos funcionales).
- Servir como documentación detallada de los casos de uso y comportamientos esperados.
- Facilidad para realizar cambios y refactorizaciones con la seguridad de que no se introducen errores.

### Que pruebas contemplan los proyectos en bootcamp

Existen distintos tipos de testing previamente configurados en los proyectos y test como estudiantes vale la pena invertir tiempo en crearlos para asegurar la calidad del código.

#### Test unitarios

Un test unitario es una pequeña pieza de código que verifica si una parte del código, (habitualmente una función), funciona correctamente, los tests unitarios se utilizan para asegurarse de que cada parte individual de un programa hace lo que se supone que debe hacer.

#### Test de integración

Un test de integración es una prueba que verifica si todas las partes diferentes de un programa funcionan bien juntas. Imagina que estás construyendo un rompecabezas y quieres asegurarte de que todas las piezas encajen correctamente. A diferencia del test unitario el test de integración no mira cada pieza individualmente, todo lo contrario, un test de integración se centra en cómo se comportan todas esas piezas cuando trabajan juntas.

#### Test e2e

Un test end-to-end (E2E) es una prueba que prueba la experiencia completa de la usuaria, desde el inicio hasta el final, como si fuera una usuaria real interactuando con una aplicación. Imagina que eres una clienta que usa una aplicación: haces clic en botones, llenas formularios y navegas por diferentes páginas el test E2E verificar si la aplicación funciona como debería desde el punto de vista de la usuaria. Similar a tener a alguien que prueba cada parte de la aplicación, desde el principio hasta el final, para asegurarse de que todo funcione correctamente.

## Buenas prácticas

- Hablar sobre la diferencia entre el test vs correr el pretest la relevancia que tiene eslint en el ciclo de vida de su proyecto.
- Hablar sobre el patrón AAA en el test
"Arrange, Act, Assert":
  - Arrange (acomodar el Ambiente): En esta etapa, se establecen las condiciones iniciales y se configuran los objetos necesarios para la prueba. Esto puede incluir la creación de objetos, la configuración de variables y la preparación del entorno de prueba.
  - Act (Actuar): En esta etapa, se lleva a cabo la acción o el comportamiento que se está probando. Es la ejecución del código que se está evaluando.
  - Assert (Afirmar): Aquí se verifica el resultado esperado de la acción realizada en la etapa anterior. Se comprueba si el resultado coincide con lo que se espera según la lógica de la prueba. Si la afirmación es verdadera, la prueba pasa; de lo contrario, falla.
- Hablar sobre convenciones utilizando jest
  - Estructuración de pruebas utilizando describe e it.
  - Implementación de aserciones con expect.
  - String con afirmaciones completas de lo que debería hacer
- Grabar la sesión
- Algunos Mantras sobre Testing en Laboratoria
  - AAA: Acomodar el Ambiente, ejecutar Acción. Finalmente Afirmar lo esperado.
  - Evitar probar detalles de implementación (probar lo que hace, no tanto cómo lo hace)
  - Es mejor pedir perdón que permiso (ej.: ejecutar la función, en lugar de verificar que sea una función).
  - Los tests deberían ser un reflejo de las historias de usuario (de la especificación, spec).
