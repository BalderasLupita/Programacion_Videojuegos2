Reporte de Avances: Programación de Videojuegos 2D en Unity

Estudiante: BalderasCortezMaria Guadalupe

Proyecto: Juego de Plataformas 2D

Videos cubiertos: 1 al 6

1. Resumen

En este bloque de seis videos, se han sentado las bases del videojuego, pasando desde la configuración inicial del motor hasta la implementación de mecánicas de juego, enemigos y gestión de niveles.

2. Desglose de Evidencias por Video

Video 1: Configuración del Entorno y Player

Lo que se hizo: Importación de assets, configuración de la escena y creación del objeto jugador.

Conceptos clave: Sprite Renderer, Rigidbody2D y BoxCollider2D.

Video 2: Movimiento del Personaje

Lo que se hizo: Programación del script de movimiento horizontal y salto.

Conceptos clave: Input.GetAxis, Velocity y fuerzas de salto.

Video 3: Sistema de Animaciones

Lo que se hizo: Creación de los estados de animación (Idle, Run, Jump) y configuración del Animator.

Conceptos clave: Transiciones, Parámetros (bool/float) y Sprite Sheets.

Video 4: Coleccionables (Frutas)

Lo que se hizo: Creación de objetos recolectables que desaparecen al contacto con el jugador.

Conceptos clave: OnTriggerEnter2D, Prefabs y destrucción de objetos.

Video 5: Enemigos y Obstáculos

Lo que se hizo: Implementación de pinchos y enemigos con movimiento oscilante. Se configuró el sistema de daño que destruye al jugador al contacto [04:01].

Conceptos clave: Animación por frames, scripts de daño 

Video 6: Gestión de Victoria y Niveles
Lo que se hizo: Creación de un Fruit Manager para contar las frutas. Al recolectar todas, el sistema detecta que no quedan hijos en el objeto contenedor y muestra un mensaje de victoria

Conceptos clave: childCount, métodos públicos y búsqueda de objetos por tipo.

4. Conclusión
Hasta el momento, el proyecto cuenta con un flujo de juego funcional: el jugador puede moverse, recolectar objetivos y perder ante obstáculos.[Video1-6_MGBC.docx](https://github.com/user-attachments/files/25307957/Video1-6_MGBC.docx)

Videos cubiertos: 7 al 14
1. Resumen
En este segundo bloque, el proyecto ha evolucionado de una base funcional a un sistema robusto y escalable. Se implementaron mecánicas avanzadas de movimiento (doble salto y caída), sistemas de plataformas móviles, y una arquitectura profesional para la selección de personajes (Skins) y menús interactivos, culminando con la adaptación del juego para dispositivos móviles.

2. Desglose de Evidencias por Video
Video 7 y 8: Doble Salto y Mecánica de Caída
Lo que se hizo: Mejora del script de movimiento para permitir un segundo salto en el aire y detección de estados de caída.

Conceptos clave: Jump Count, Velocity.y (detección de caída) y actualización de parámetros en el Animator.

Video 9: Plataformas Móviles y Efecto "Parent"
Lo que se hizo: Creación de plataformas que se mueven entre dos puntos. Se configuró para que el jugador se mueva junto con la plataforma al estar sobre ella.

Conceptos clave: MoveTowards, OnCollisionEnter2D (hacer al jugador hijo de la plataforma) y OnCollisionExit2D.

Video 10: Plataformas de un solo sentido (One-Way Platforms)
Lo que se hizo: Implementación de plataformas por las que el jugador puede saltar desde abajo pero mantenerse firme arriba.

Conceptos clave: Platform Effector 2D, Rotational Offset y capas de colisión (Layers).

Video 11: Sistema de Skins y Prefab Maestro
Lo que se hizo: Reestructuración del jugador en un "Prefab Maestro" capaz de cambiar su apariencia y animaciones dinámicamente.

Conceptos clave: Animator Override Controllers, estructuras de datos para personajes y optimización de prefabs.

Video 12: Menú Principal Jugable (Lobby)
Lo que se hizo: Creación de un nivel central donde el jugador camina hacia puertas para acceder a diferentes niveles.

Conceptos clave: SceneManager.LoadScene, disparadores de proximidad (Triggers) y diseño de niveles tipo "Hub".

Video 13: Selector de Personajes Visual (UI)
Lo que se hizo: Implementación de una interfaz con botones para elegir personajes en tiempo real, guardando la elección de forma persistente.

Conceptos clave: PlayerPrefs (persistencia de datos), eventos OnClick y paneles de UI.

Video 14: Controles para Móvil
Lo que se hizo: Adaptación del juego para pantallas táctiles mediante la integración de un Joystick virtual y botones en pantalla.

Conceptos clave: Joystick Pack, Canvas Scaler (adaptación a resoluciones) y mapeo de inputs táctiles.

3. Conclusión
El videojuego ha dejado de ser un prototipo simple para convertirse en un proyecto completo. Ahora cuenta con persistencia de datos, una interfaz de usuario funcional, un sistema de personalización y es totalmente compatible con dispositivos móviles. Las bases de arquitectura creadas permiten expandir el juego con infinitos niveles y personajes de manera sencilla.
[Video7-14_MGBC.docx](https://github.com/user-attachments/files/25580578/Video7-14_MGBC.docx)

Videos de lo que se hizo https://drive.google.com/drive/folders/1yg1KaqKkBqxQTIfScT59zaMyC2OetkLW?usp=sharing 
