# Guías de Entrega — Programación Avanzada
 
Guías interactivas paso a paso para estudiantes de **Programación Avanzada (Java Web)** — Bachillerato Tecnológico, UTU (DGETP).
 
Cada guía es un archivo HTML autocontenido que se abre directamente en el navegador, sin necesidad de instalar nada. Presenta los pasos de entrega organizados en un asistente con pestañas por actividad (básico / intermedio / avanzado) y avance por pasos numerados.
 
---
 
## Guías disponibles
 
### `guia-entrega-minicrud_1.html`
**PRACTICA 1 — Mini CRUD básico**  
Introduce la estructura MVC con JSP y Servlets. El estudiante descarga el proyecto base, agrega los archivos indicados y despliega el CRUD de Personas con las operaciones de listar y agregar.
 
---
 
### `guia-entrega-minicrud_2.html`
**PRACTICA 2 — Mini CRUD con edición y eliminación**  
Extiende el proyecto anterior incorporando las operaciones de editar y eliminar, completando el ciclo CRUD completo. La actividad avanzada propone implementar el mismo CRUD sobre una entidad propia elegida por el estudiante.
 
**Actividades:**
- **Act. 01 — Básico:** agregar editar y eliminar al proyecto existente
- **Act. 02 — Intermedio:** aplicar el patrón PRG (Post/Redirect/Get)
- **Act. 03 — Avanzado:** replicar el CRUD con una entidad propia (Producto, Libro, Película, Videojuego, Estudiante u otra acordada con la docente)
  
---
 
### `guia-entrega-minicrud_3.html`
**PRACTICO 3 — Base de Datos y Herencia**  
Incorpora una segunda tabla con clave foránea y herencia de clases Java (`DocenteVO extends PersonaVO`). Cubre el manejo de `ALTER TABLE`, `CREATE TABLE` con `FOREIGN KEY … ON DELETE CASCADE` y la adaptación del DAO para múltiples tablas.
 
**Actividades:**
- **Act. 01 — Básico:** agregar la columna `fecha_nacimiento` a la tabla existente y actualizar el DAO
- **Act. 02 — Intermedio:** implementar búsqueda por nombre con `LIKE` usando GET
- **Act. 03 — Avanzado:** agregar la entidad `Docente` con herencia de `Persona` (tabla hija + FK)

---
 
## Cómo usar las guías
 
Abrir el archivo `.html` en cualquier navegador moderno. No requiere servidor ni conexión a internet.
 
La guía recuerda en qué paso quedó el estudiante mientras la pestaña del navegador permanezca abierta. Al cerrarla, el avance se reinicia desde el paso 0.
 
---
 
## Stack del curso
 
| Componente | Versión |
|---|---|
| Java | JDK 17 |
| Jakarta EE (Servlets / JSP) | 6.x |
| Maven | 3.x |
| Tomcat (vía cargo) | 10.1.57 |
| MySQL Connector/J | 8.3.0 |
| IDE | VS Code + Extension Pack for Java |
 
---
 
## Estructura del repositorio
 
```
guias-entrega/
├── guia-entrega-minicrud.html
├── guia-entrega-minicrud2.html
├── guia-entrega-BD-herencia.html
└── README.md
```
 
---
 
*Prof. Elizabeth Izquierdo — Programación Avanzada · Bachillerato Tecnológico · UTU (DGETP)*
