#  Patrones de Diseño
## Carlos Andrés Muñoz Buitrago
### Desarrollo  y Arquitectura de Software
|Metódo|Tipo de patrón de diseño| Descripción|
|---------------|-----------------|-------------------|
-|Creacional|Herramienta usada para la creación de objetos dinámicos y reutilización de código que se esté utilizando en un proyecto debido.
Factory|Creacional|Interfaz conformadas de una superclase y subclases para generar e implementar objetos.
Abstract|Creacional|Método que crea las variantes de los diferentes objetos existentes sin especificar sus clases respectivas.
Builder|Creacional|Construye, organiza y genera objetos relacionados complejos que pueden ser representadas de diversas maneras usando el código existente.
Prototype|Creacional|Crea una copia de los objetos existentes que no dependen de sus clases respectivas.
Singleton|Creacional|Controla la creación de una sola instancia de un objeto y genera un punto de acceso global y privado al objeto en cuestión.
-|Estructural|Patron que permite el ensamble de objetos y clases en estructuras grandes, manejables y eficientes.
Adapter|Estructural| Permite la conexión entre objetos con interfaces incompatibles
Brigde|Estructural| Divide una clase en dos jerarquías: abstracción e implementación, que se desarrollan por separado.
Composite| Estructural| Integra los objetos dentro de árboles y se manejan como hojas(estructuras individuales).
Decorator|Estructural|Encapsula en objetos y añade funcionalidades a objetos o funciones que están contenidas en estas.
Facade|Estructural|Interfaz que simplifica frameworks, bibliotecas y otras clases complejas.
Flyweight|Estructural|Permite obtener más objetos por fuera de la cantidad de RAM(Random Access Memory) manteniendo solo las partes comunes del estado de varios objetos de toda la información contenida.
Proxy|Estructural|Genera un acceso al objeto original que crea un sustituto que permite modificarlo mientras este se encuentre en el proxy para una solitud requerida.
-|Comportamiento|Son algoritmos y asignación de responsabilidades entre objetos.
Chain of Responsability|Comportamiento|Son un conjunto manejadores que reciben solitudes que procesan o deciden si  pasarla al siguiente manejador.
Command|Comportamiento|Transforma una solitud en un objeto independiente que contiene toda su información, que permite parametrizar los métodos en solitudes, contralar la ejecución del mismo y  realizar operaciones no efectuables.
Iterator|Comportamiento|Permite recorrer una estructura de datos sin mostrar la forma de los datos contenidos en este.
Mediator|Comportamiento|Restringue las comunicaciones entre los objetos por medio de un objeto mediador para reducir las dependencias entre estos objetos.
Memento|Comportamiento|Permite guardar y restaurar objetos sin dar información acerca de su implementación.
Observer|Comportamiento|Define un mecanismo de suscripción, para avisar los eventos que presente en un objeto a un objeto 'observador' determinado.
State|Comportamiento|Permite el cambio del comportamiento de un objeto basado en los cambios en sus estados internos
Strategy|Comportamiento|Permite realizar familias de algoritmos con definidas con clases distintas y objetos intercambiables.
Template|Comportamiento|Permite que un algoritmo sea almacenada en una superclase y que susu subclases alteren los pasos del algoritmo sin cambiar la estructura general de este mismo.
Visitor|Comportamiento|Permite separar los algoritmos sobre los objetos que operan.
# Bibliografia:
[Refactoring Guru](https://refactoring.guru/es/design-patterns)
