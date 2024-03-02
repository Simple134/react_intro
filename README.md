# React

## Que es React.js?
React.js, comúnmente conocido como React, es una biblioteca de JavaScript utilizada para construir interfaces de usuario interactivas y reutilizables. Fue desarrollado por Facebook y es mantenido por Facebook e Instagram, así como por una comunidad de desarrolladores individuales y empresas.

React se utiliza para crear componentes de interfaz de usuario que pueden actualizarse de manera eficiente cuando cambian los datos. Se basa en el concepto de "componentes", que son bloques de construcción reutilizables para construir interfaces de usuario. Cada componente tiene su propio estado y puede renderizarse de manera independiente en la interfaz de usuario.

Una de las características clave de React es su capacidad para realizar actualizaciones eficientes del DOM (Document Object Model). Utiliza un enfoque llamado "virtual DOM", que es una representación virtual de la estructura de la interfaz de usuario en memoria. Cuando cambia el estado de un componente, React compara el virtual DOM anterior con el nuevo y actualiza solo las partes del DOM que han cambiado, en lugar de actualizar todo el árbol del DOM. Esto mejora significativamente el rendimiento y la eficiencia de las aplicaciones.

React se utiliza comúnmente en conjunto con otras bibliotecas y herramientas, como Redux para la gestión del estado y React Router para la navegación en aplicaciones de una sola página (SPA). React se ha vuelto muy popular en el desarrollo web y es ampliamente adoptado en la industria

## Diferencias

- Routing:

React en sí no proporciona enrutamiento directamente, pero suele trabajar en conjunto con bibliotecas de enrutamiento como React Router. Pueden haber mejoras en la integración o funcionalidades adicionales en las bibliotecas de enrutamiento.

- Rendering:

React generalmente mejora el rendimiento y la eficiencia en cada versión. La introducción de nuevas técnicas de renderizado o mejoras en el manejo del DOM virtual podrían ser áreas de enfoque.
Data Fetching:

React se ha movido hacia un modelo más declarativo en cuanto a la gestión del estado y la obtención de datos. Pueden haber mejoras en la forma en que se maneja la obtención de datos, como la integración con nuevas API o técnicas.

- Styling:

En términos de estilos, React permite diferentes enfoques, desde el uso de CSS estándar hasta bibliotecas de estilos en línea y soluciones más avanzadas como Styled Components. Cambios en la forma en que se manejan los estilos o mejoras en la integración de herramientas de estilo son posibles.

- Optimizaciones:

Cada nueva versión suele incluir mejoras de rendimiento y optimizaciones. Estas pueden abordar cuestiones específicas, como la reducción del tamaño del paquete, la mejora del rendimiento de la aplicación o la optimización del tiempo de carga.

- Typescript:
La compatibilidad con TypeScript ha sido una prioridad en versiones recientes de React. Pueden haber mejoras en la integración de TypeScript y en el soporte para tipos estáticos en componentes.

## Componentes (Components):

En React, los componentes son bloques de construcción reutilizables para construir interfaces de usuario. Pueden considerarse como pequeñas piezas independientes de la interfaz que encapsulan el comportamiento y la presentación. Los componentes pueden ser funcionales o basados en clases, y permiten dividir la interfaz de usuario en partes más pequeñas y manejables.

## JSX:

 JSX, o JavaScript XML, es una extensión de sintaxis de JavaScript que permite escribir código HTML de manera similar dentro de archivos JavaScript. JSX facilita la creación de estructuras de interfaz de usuario en React de manera más legible y declarativa. Aunque se parece a HTML, JSX se compila finalmente a llamadas de funciones de JavaScript.

## Props:

Las "props" (abreviatura de propiedades) son objetos que contienen información que se pasa de un componente padre a un componente hijo en React. Estas propiedades permiten que los componentes se comuniquen y compartan datos. Las props son inmutables (no pueden ser modificadas por el componente hijo) y son una forma eficiente de pasar datos a través de la jerarquía de componentes.

## Estado (State):

El estado en React representa la información dinámica que puede cambiar durante la vida de un componente. Mientras que las props se utilizan para pasar datos de un componente padre a un componente hijo, el estado se utiliza para gestionar datos que pueden cambiar dentro del propio componente. Los componentes de clase tienen estado, mientras que los componentes funcionales con Hooks también pueden tener estado mediante el hook useState.

## Composite

El patrón de diseño estructural Composite es un patrón que se utiliza para componer objetos en estructuras de árbol para representar jerarquías parte-todo. Este patrón permite a los clientes tratar objetos individuales y composiciones de objetos de manera uniforme.

En el patrón Composite, se define una interfaz común para tanto los objetos individuales (hojas) como las composiciones de objetos (nodos). Esto permite que los clientes traten a ambos tipos de objetos de manera uniforme, ya que ambos cumplen con la misma interfaz.

## State
El patrón de diseño estructural llamado "State" se centra en gestionar el estado interno de un objeto de manera que su comportamiento pueda cambiar en función de este estado. En lugar de tener múltiples clases con comportamientos específicos, el objeto altera su comportamiento a medida que cambia su estado interno.

Características clave del patrón State:

- Interfaz común: Define una interfaz común para todas las clases que representan los diferentes estados. Esto permite que los objetos que utilizan el estado no estén acoplados directamente a clases específicas de estado.

- Clases de estado concretas: Cada clase concreta representa un estado específico y proporciona implementaciones concretas para los métodos definidos en la interfaz común.

- Transiciones de estado: Permite la transición entre diferentes estados mediante métodos que cambian el estado interno del objeto.

- Contexto: El objeto que contiene el estado tiene un "contexto" que se encarga de cambiar dinámicamente su comportamiento a medida que cambia su estado.
