# Guías de Entrega — Programación Avanzada
 
Guías interactivas paso a paso para estudiantes de **Programación Avanzada (Java Web)** — Bachillerato Tecnológico, UTU (DGETP).
 
Cada guía es un archivo HTML autocontenido que se abre directamente en el navegador, sin necesidad de instalar nada. Presenta los pasos de entrega organizados en un asistente con pestañas por actividad (básico / intermedio / avanzado) y avance por pasos numerados.
 
---
 
## Guías disponibles
 
| Práctica | Tema | Guía |
|---|---|---|
| 1 | Mini CRUD básico | [Abrir guía 1](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_1.html) |
| 2 | Mini CRUD con edición y eliminación | [Abrir guía 2](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_2.html) |
| 3 | Mini CRUD con Base de Datos | [Abrir guía 3](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_3.html) |
| 4 | CRUD completo con Base de Datos | [Abrir guía 4](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_4.html) |
| 5 | Herencia en la Base de Datos | [Abrir guía 5](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_5.html) |
 
### [`guia-entrega-minicrud_1.html`](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_1.html)
**PRÁCTICA 1 — Mini CRUD básico**  
Introduce la estructura MVC con JSP y Servlets. El estudiante descarga el proyecto base, agrega los archivos indicados y despliega el CRUD de Personas con las operaciones de listar y agregar.
 
---
 
### [`guia-entrega-minicrud_2.html`](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_2.html)
**PRÁCTICA 2 — Mini CRUD con edición y eliminación**  
Extiende el proyecto anterior incorporando las operaciones de editar y eliminar, completando el ciclo CRUD completo. La actividad avanzada propone implementar el mismo CRUD sobre una entidad propia elegida por el estudiante.
 
**Actividades:**
- **Act. 01 — Básico:** ampliar la entidad Persona con teléfono y dirección en el alta, el listado y la edición
- **Act. 02 — Intermedio:** validar los datos del lado del servidor al agregar y al editar
- **Act. 03 — Avanzado:** replicar el CRUD con una entidad propia (Producto, Libro, Película, Videojuego, Estudiante u otra acordada con la docente)
---
 
### [`guia-entrega-minicrud_3.html`](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_3.html)
**PRÁCTICA 3 — Base de Datos (consultas)**  
Trae datos de MySQL con JDBC aplicando las 5 fases del acceso a datos. En esta práctica el DAO solo hace consultas (`SELECT`): los datos se cargan directamente en MySQL con `INSERT` y `UPDATE`. Agregar, actualizar y eliminar desde la aplicación se trabajará en las próximas clases.

**Actividades:**
- **Act. 01 — Básico:** agregar la columna `fecha_nacimiento`, cargar fechas en MySQL y mostrarlas en el listado (`getLista()`)
- **Act. 02 — Intermedio:** implementar búsqueda por nombre con `LIKE` usando GET
- **Act. 03 — Avanzado:** llevar la entidad propia de la Práctica 2 a MySQL: tabla, conexión y listado desde la base de datos

---

### [`guia-entrega-minicrud_4.html`](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_4.html)
**PRÁCTICA 4 — CRUD completo con Base de Datos**  
El instituto decidió registrar también el sueldo de cada persona. Se agrega el atributo nuevo en todas las capas y se completan los métodos del DAO para agregar, buscar por código, actualizar y eliminar directamente en MySQL, hasta que el `ArrayList` en memoria desaparece del proyecto.

**Actividades:**
- **Act. 01 — Básico:** agregar la columna `sueldo`, mostrarla en el listado y dar de alta personas desde la aplicación (`agregar()` y `obtenerXCodigo()` con JDBC)
- **Act. 02 — Intermedio:** editar y eliminar personas en la BD (`actualizar()` y `eliminar()` con JDBC) y quitar el `ArrayList` del DAO
- **Act. 03 — Avanzado:** CRUD completo de la entidad propia en MySQL, con un atributo numérico nuevo

---

### [`guia-entrega-minicrud_5.html`](https://programacion2do.github.io/MiniCRUD-Practicas/guia-entrega-minicrud_5.html)
**PRÁCTICA 5 — Herencia en la Base de Datos**  
El instituto necesita registrar a sus profesores. `ProfesorVO` hereda de `PersonaVO` (con especialidad y horas semanales) y en MySQL la tabla `profesores` se une a `personas` por el código, con clave foránea, `INNER JOIN` y transacciones.

**Actividades:**
- **Act. 01 — Básico:** crear la tabla `profesores`, la clase `ProfesorVO` y el listado de profesores con `INNER JOIN`
- **Act. 02 — Intermedio:** alta y edición de profesores con transacciones (`commit` / `rollback`) y baja con `ON DELETE CASCADE`
- **Act. 03 — Avanzado:** agregar una subclase a la entidad propia, con su tabla hija y su CRUD completo

---
 
## Material complementario
 
### Guías de apoyo
 
| Material | Descripción |
|---|---|
| [Cómo entregar la actividad MiniCRUD en GitHub](https://programacion2do.github.io/MiniCRUD-Practicas/Guia-entrega-GitHub.html) | Pasos para subir el proyecto a GitHub y realizar la entrega. |
| [Guía MVC — Proyecto Mini-CRUD](https://programacion2do.github.io/MiniCRUD-Practicas/guia-mvc-crema-tinta.html) | Explicación de la arquitectura MVC aplicada al proyecto Mini-CRUD. |
 
### Consignas en PDF
 
| Práctica | Archivo |
|---|---|
| 1 | [practica-minicrud_1.pdf](https://programacion2do.github.io/MiniCRUD-Practicas/practica-minicrud_1.pdf) |
| 2 | [practica-minicrud_2.pdf](https://programacion2do.github.io/MiniCRUD-Practicas/practica-minicrud_2.pdf) |
| 3 | [practica-minicrud_3.pdf](https://programacion2do.github.io/MiniCRUD-Practicas/practica-minicrud_3.pdf) |
| 4 | [practica-minicrud_4.pdf](https://programacion2do.github.io/MiniCRUD-Practicas/practica-minicrud_4.pdf) |
| 5 | [practica-minicrud_5.pdf](https://programacion2do.github.io/MiniCRUD-Practicas/practica-minicrud_5.pdf) |
 
---
 
## Cómo usar las guías
 
Abrir el enlace de la guía en cualquier navegador moderno. También es posible descargar el archivo `.html` y abrirlo localmente: no requiere servidor ni conexión a internet.
 
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
 
```text
MiniCRUD-Practicas/
├── guia-entrega-minicrud_1.html
├── guia-entrega-minicrud_2.html
├── guia-entrega-minicrud_3.html
├── guia-entrega-minicrud_4.html
├── guia-entrega-minicrud_5.html
├── Guia-entrega-GitHub.html
├── guia-mvc-crema-tinta.html
├── practica-minicrud_1.pdf
├── practica-minicrud_2.pdf
├── practica-minicrud_3.pdf
├── practica-minicrud_4.pdf
├── practica-minicrud_5.pdf
└── README.md
```
 
---
 
*Prof. Elizabeth Izquierdo — Programación Avanzada · Bachillerato Tecnológico · UTU (DGETP)*
