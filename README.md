Pregunta 1: ¿Cuál es la principal ventaja de la compilación anticipada AOT (Ahead-of-Time) introducida
en el Android Runtime (ART) en comparación con el modelo tradicional de la JVM?

B) Traduce el bytecode a código de máquina nativo previo al inicio de la ejecución, mejorando la velocidad de inicio de la app y disminuyendo el uso de la batería.

Pregunta 2: ¿Cuál es la responsabilidad primordial del Linux Kernel dentro de la arquitectura de capas
del sistema operativo Android?

B) Proveer APIs públicas de alto nivel en lenguaje Java para el uso directo de los desarrolladores en sus Activities.

Pregunta 3: ¿Qué función cumple la capa HAL (Hardware Abstraction Layer) en la arquitectura interna
de Android?

A) Define interfaces de software estándar para que las APIs de alto nivel de Java se comuniquen con los componentes físicos del hardware (cámara, sensores, Bluetooth) independientemente de la implementación del fabricante.

Pregunta 4: Cuando una Activity en primer plano pierde el foco de forma parcial pero sigue siendo visible para el usuario, ¿qué método de su ciclo de vida es invocado secuencialmente en primer lugar?

B) onPause(), suspendiendo operaciones que consuman CPU pero manteniendo las variables y el estado visual cargados en memoria.

Pregunta 5: Si se invoca un Intent explícito para navegar a una pantalla de confirmación, pero esta
pantalla no se encuentra registrada en el archivo AndroidManifest.xml, ¿qué sucede en tiempo de
ejecución?

D) La aplicación se detiene inmediatamente arrojando un error crítico de tipo ActivityNotFoundException.

Pregunta 6: Dentro de los componentes estructurales de una aplicación en Android, ¿cuál es el
objetivo técnico de un Content Provider?

B) Administrar y centralizar el acceso a repositorios de datos locales de forma segura, permitiendo el intercambio
controlado de información entre distintas aplicaciones.

Pregunta 7: ¿En qué escenario del desarrollo de Android es obligatorio el uso de un Intent de tipo
Explícito?

A) Cuando se solicita al sistema operativo abrir la aplicación de mapas externa para trazar una ruta.

Pregunta 8: Cuando una Activity es enviada a segundo plano e ingresa en el estado de Detenida
(onStop()), y el sistema operativo sufre de una necesidad crítica de memoria RAM para priorizar
llamadas de voz u otras apps, ¿qué acción toma el sistema?

C) Puede matar silenciosamente el proceso de la aplicación, forzando la recreación completa (onCreate()) de la Activity
cuando el usuario regrese a ella.


