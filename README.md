# 🎮 Proyecto: Juego de Plataformas 2D en Unity
**Estudiante:** Balderas Cortez Maria Guadalupe  
**Curso:** Programación de Videojuegos 2D  
**Motor:** Unity 2022.x / 2023.x

---

## 📝 Resumen del Proyecto
Este repositorio contiene el progreso detallado del desarrollo de un videojuego de plataformas 2D, abarcando desde la configuración básica del motor hasta sistemas avanzados de personalización (Skins) y adaptación para dispositivos móviles.

---

## 🕹️ Bitácora de Desarrollo (Videos 1 - 6)
> **Estado:** 🟢 Funcionalidades Básicas Completadas

En este bloque se sentaron las bases del juego, el movimiento físico y la lógica de recolección.

| Fase | Módulo | Implementación Clave | Conceptos Unity |
| :--- | :--- | :--- | :--- |
| **01** | **Entorno** | Importación de Assets y Player. | `Sprite Renderer`, `RigidBody2D` |
| **02** | **Movimiento** | Script de control horizontal y salto. | `Input.GetAxis`, `Velocity` |
| **03** | **Animación** | Estados Idle, Run y Jump. | `Animator Controller`, `Parameters` |
| **04** | **Items** | Coleccionables (Frutas). | `OnTriggerEnter2D`, `Prefabs` |
| **05** | **Obstáculos** | Enemigos y sistema de daño. | `Collision Detection`, `Scripts` |
| **06** | **Victoria** | Fruit Manager y conteo de niveles. | `childCount`, `Object Discovery` |

📂 [Descargar Reporte Detallado Videos 1-6](https://github.com/user-attachments/files/25307957/Video1-6_MGBC.docx)

---

## 🚀 Sistemas Avanzados (Videos 7 - 14)
> **Estado:** 🔵 Arquitectura y UX Escalable

El proyecto evolucionó de un prototipo a un sistema robusto preparado para publicación.

### ✨ Mecánicas y Funcionalidades
* **Doble Salto y Caída:** Refinamiento de la fluidez del salto (Videos 7-8).
* **Plataformas Inteligentes:** * *Móviles:* Sincronización de movimiento Jugador-Plataforma (Video 9).
    * *One-Way:* Uso de `Platform Effector 2D` (Video 10).
* **Arquitectura de Personajes:** Sistema de **Skins** mediante `Animator Override Controllers` y Prefabs Maestros (Video 11).
* **Interfaz y Navegación:** * Lobby interactivo (Nivel Central).
    * Menú de Selección de Personajes con **Persistencia de Datos** (`PlayerPrefs`).
* **Soporte Mobile:** Integración de Joystick virtual y UI adaptable (Video 14).

📂 [Descargar Reporte Detallado Videos 7-14](https://github.com/user-attachments/files/25580578/Video7-14_MGBC.docx)

---

## 🛠️ Tecnologías Utilizadas
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📺 Evidencias en Video
Puedes ver el proceso de desarrollo y las pruebas de juego en el siguiente enlace:
👉 [Google Drive - Evidencias de Video](https://drive.google.com/drive/folders/1yg1KaqKkBqxQTIfScT59zaMyC2OetkLW?usp=sharing)

---

## 🏁 Conclusión
El videojuego ha pasado de ser un prototipo simple a un proyecto completo con persistencia de datos, interfaz funcional y compatibilidad móvil. Las bases creadas permiten expandir el juego con nuevos niveles y personajes de manera eficiente.
