# Capítulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.

Esta guía define las decisiones y acuerdos fundamentales para el desarrollo, mantenimiento y despliegue de la aplicación **CultiConnection**, que gestiona el alquiler de vehículos. El objetivo es asegurar la coherencia, eficiencia y calidad a lo largo del ciclo de vida del proyecto.

---

### 5.1.1. Software Development Environment Configuration.

<table border="1">

  <tr>
    <td>Project Management</td>
    <td><h4>Github</h4>Plataforma en línea que permite almacenar código fuente en repositorios. Gracias a la tecnología de control de versiones de Git se puede organizar el código y llevar un mejor trabajo en conjunto.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Whatsapp</h4>Red Social destinada a la comunicación donde se realizaron acuerdos y recordatorios de las reuniones.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Trello</h4>Software de administración y gestión de proyectos que se utilizó para establecer y designar las tareas</td>
  </tr>
  <tr>
    <td>Requirements Management</td>
    <td><h4>Miro</h4>Plataforma en línea de gestión de requisitos que permite colaborar y organizar proyectos de forma visual y representativa.
</td>
  </tr>
  <tr>
    <td>Product UX/UI Design</td>
    <td><h4>Figma</h4>Aplicación que permite el diseño libre de interfaces a través de las múltiples herramientas que ofrece. Permitiendo la creación de prototipos interactivos que simulan la experiencia de usuario.
</td>
  </tr>
  <tr>
    <td>Software Development</td>
    <td><h4>Git</h4>Es un software de control de versiones para los trabajos en equipos y confiabilidad del desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Node.js</h4>Node.js es un entorno de ejecución de JavaScript del lado del servidor, que permite desarrollar aplicaciones web escalables y de alto rendimiento fuera del navegador.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>HTML</h4>Lenguaje de etiquetas, utilizado para la estructuración y la presentación de contenido.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>CSS</h4>CSS es un lenguaje utilizado para estilizar y dar formato a documentos HTML.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>JavaScript</h4>JavaScript es un lenguaje de programación de alto nivel, interpretado y multi-paradigma, utilizado para crear interactividad en páginas web.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>VSCode</h4>Es un editor de código fuente con extensiones que ayudan al desarrollo.</td>
  </tr>
    <tr>
    <td></td>
    <td><h4>WebStorm</h4>Es un IDE centrado en el desarrollo frontend, por su variedad de herramientas que agilizan el proceso de desarrollo.</td>
  </tr>
  <tr>
    <td></td>
    <td><h4>Vue.js</h4>Framework basado en Single Page Applications para el desarrollo de frontend</td>
  </tr>
  <tr>
    <td>Software Deployment</td>
    <td><h4>Github Pages</h4>Plataforma que nos permite realizar el despliegue de nuestro landing page.</td>
  </tr>
</table>

---

### 5.1.2. Source Code Management.

Hemos optado por crear un repositorio en GitHub para nuestro proyecto, tanto para el informe como para la landing page. Esto facilitó la colaboración entre los miembros del equipo,aprovechando las herramientas útiles que esta plataforma ofrece para el manejo del código fuente y sus versiones.


- URL del repositorio Report en GitHub: https://github.com/Apps-Web-Grupo-4-FruTech/ReportFinalProject
- URL del repositorio Landing Page en GitHub: https://github.com/Apps-Web-Grupo-4-FruTech/Landing-Page
- URL del repositorio Frontend en GitHub: https://github.com/Apps-Web-Grupo-4-FruTech/Frontend-FruTech

---


### 5.1.3. Source Code Style Guide & Conventions.

Para "**CultiConnection**", hemos utilizado "**HTML y CSS**". Para estructurar el contenido usamos etiquetas de section y divisiones para contenido específico de cada una de las secciones. Además, hemos empleado atributos como ***HTML Style*** para personalizar el aspecto visual, definiendo propiedades como color, tamaño de fuente y tipo de letra.

Para resaltar elementos importantes, hemos aplicado ***HTML Text Formatting***, incluyendo etiquetas como b para negrita, strong para resaltado y del para mostrar cambios de precios. En cuanto a la navegación, hemos implementado una barra de navegación horizontal utilizando **CSS** para mejorar la experiencia del usuario al explorar el contenido.

Los formularios, creados con **CSS**, permiten a los usuarios ingresar información relevante, como detalles de inicio de sesión, información de pago y dirección de envío. Para añadir interactividad, hemos agregado botones con efectos hover utilizando CSS y paginación CSS para facilitar la navegación entre las diferentes páginas de productos.

Finalmente, en el **footer**, hemos incluido enlaces a las redes sociales de la organización para brindar a los usuarios una forma adicional de conectarse y seguir nuestras actualizaciones.

### 5.1.4. Software Deployment Configuration.

Utilizaremos GitHub Pages para alojar nuestra Landing Page. Para lograrlo, subiremos los archivos esenciales (HTML, CSS, etc.) a un repositorio público en GitHub. De
esta manera, nuestra página estará disponible en línea y accesible para todos los usuarios.

![GithubReportRepo](assets/github-repo.png)

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

| Elemento                        | Detalle                                                                                       |
|----------------------------------|----------------------------------------------------------------------------------------------|
| **Sprint**                      | 1 - Implementación de funcionalidades básicas y diseño inicial de CultiConnection                   |
| **Sprint Planning Background**   |                                                                                              |
| **Fecha**                       | 20/09/2025                                                                                   |
| **Hora**                        | 20:00 horas (GMT-5)                                                                          |
| **Lugar**                       | Reunión virtual mediante Discord                                                              |
| **Preparado por**               | [FruTech]                                                       |
| **Asistentes**                  | [ Samuel Bonifacio , Jefferson Castro, Bruce Via, Sergio Landa, Estefano Solis ]                                                             |
| **Sprint n-1 Review**           | Se creó la organización de CultiConnection en GitHub, se definieron ramas y se asignaron tareas iniciales como investigación de usuarios, wireframes y mockups. |
| **Sprint n-1 Retrospective**    | Se implementó la estructura básica de la landing page utilizando HTML, CSS y JavaScript.      |
| **Sprint Goal & User Stories**  |                                                                                              |
| **Sprint 1 Velocity**           | 20 puntos                                                                                    |
| **Sum of Story Points**         | 20 puntos                                                                                    |

#### Objetivo del Sprint
Implementar la estructura inicial de la aplicación, el diseño de la landing page y las funcionalidades básicas de registro e inicio de sesión para los usuarios de CultiConnection.

#### User Stories seleccionadas para el Sprint 1

| ID  | User Story                                                                                  | Puntos |
|-----|---------------------------------------------------------------------------------------------|--------|
| 1   | Como usuario, quiero poder registrarme en la plataforma para acceder a las funcionalidades.  |   5    |
| 2   | Como usuario, quiero iniciar sesión para gestionar mis cultivos o recursos.                  |   5    |
| 3   | Como visitante, quiero visualizar la landing page con información clara sobre CultiConnection.     |   4    |
| 4   | Como usuario, quiero navegar entre las secciones principales desde la barra de navegación.   |   3    |
| 5   | Como usuario, quiero acceder a enlaces de contacto y redes sociales desde el footer.         |   3    |

**Total de puntos:** 20

---

#### 5.2.1.2. Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (Leadership-and-Collaboration Matrix, LACX) para el Sprint 1 de CultiConnection. Esta matriz identifica, para cada aspecto clave del Sprint, quién es el líder responsable y quiénes son los colaboradores, facilitando así la comunicación y la asignación de tareas dentro del equipo. 

Los aspectos considerados en este Sprint incluyen: diseño de la landing page, desarrollo de funcionalidades de registro e inicio de sesión, implementación de la barra de navegación, y configuración del footer con enlaces de contacto y redes sociales.

| Team Member (Apellido, Nombre)         | GitHub Username      | Landing Page Design | Registro/Inicio de Sesión | Barra de Navegación | Footer y Redes Sociales |
|----------------------------------------|----------------------|---------------------|--------------------------|---------------------|------------------------|
| Bonifacio, Samuel                     | samuelbonifacio015      | L                   | L                       | L                   | L                      |
| Castro, Jefferson                      | JeffersonCastroPariona     | C                   | L                        | C                   | C                      |
| Via, Bruce                             | Shukaritas            | C                   | C                        | L                   | C                      |                     |
| Solis, Estefano                        | Estefano-Solis-C       | C                   | C                        | C                   | C                      |
| Landa, Sergio                        | Serkekes2006       | C                   | C                        | C                   | C                      |

**L:** Leader (Líder)  
**C:** Collaborator (Colaborador)

Esta organización permite una asignación clara de responsabilidades y fomenta la colaboración efectiva durante el desarrollo del Sprint.


#### 5.2.1.3. Sprint Backlog 1

| ID   | Title/Section                | Description                                                                                      | Estimation (Hours) | Assigned To                | Status         |
|------|------------------------------|--------------------------------------------------------------------------------------------------|--------------------|----------------------------|---------------|
| US01 | Landing Page                 | Desarrollo e implementación de la estructura y estilos de la landing page. Debe ser responsive.  | 3                  | Samuel Bonifacio           | Done          |
| US02 | Registro de Usuario          | Implementación del formulario y lógica para el registro de usuarios.                             | 3                  | Jefferson Castro           | Done          |
| US03 | Inicio de Sesión             | Desarrollo del formulario y lógica para el inicio de sesión de usuarios.                         | 3                  | Jefferson Castro           | Done          |
| US04 | Barra de Navegación          | Implementación de la barra de navegación principal, con enlaces a las secciones. Responsive.     | 2                  | Sergio Landa                  | Done          |
| US05 | Footer y Redes Sociales      | Desarrollo del footer con enlaces de contacto y redes sociales. Responsive.                      | 2                  | Estefano Solis             | Done          |
| US06 | Página de Información        | Sección informativa sobre CultiConnection y sus beneficios.                                            | 2                  | Samuel Bonifacio           | Done          |
| US07 | Validación de Formularios    | Validación de datos en los formularios de registro e inicio de sesión.                           | 2                  | Jefferson Castro           | Done          |
| US08 | Estilos Generales            | Definición y aplicación de estilos globales (colores, fuentes, espaciados, etc.).                | 1                  | Bruce Via                  | Done          |

**Leyenda de Status:**  
To-do / InProcess / ToReview / Done

---
#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo de CultiConnection realizó múltiples commits en el repositorio de GitHub, evidenciando el avance y cumplimiento de las tareas planificadas. A continuación, se presenta una tabla con los principales commits realizados, siguiendo el formato requerido:

| Repository                                         | Branch | Commit Id | Commit Message                                 | Commit Message Body                                   | Committed on (Date)     |
|----------------------------------------------------|--------|-----------|------------------------------------------------|-------------------------------------------------------|------------------------|
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 42af56e   | feat: add images folder and update index.html  | Se agregó la carpeta de imágenes y se actualizó index.html. | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 5eb6b3f   | feat: add images folder and update index.html  | Se agregó la carpeta de imágenes y se actualizó index.html. | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 457c4a0   | chore: SEO and Meta tags added                 | Se añadieron mejoras en SEO y meta etiquetas.          | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 626b448   | feat: merged sections & responsive             | Se fusionaron secciones y se mejoró la responsividad.  | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | c14157e   | chore: updated logo & index                    | Se actualizó el logo y la estructura principal.        | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 879b814   | feat: added features & purchase sections       | Se añadieron secciones de características y compras.   | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 6b06fef   | feat: added responsive hamburger menu          | Se implementó el menú hamburguesa responsive.          | 20/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | c911dca   | feat: merged initial setup                     | Se realizó la configuración inicial y estructura básica de la landing page. | 19/09/2025             |
| Apps-Web-Grupo-4-FruTech/Landing-Page              | main   | 31de6c2   | feat: initial setup for landing page           | Configuración inicial para la landing page.            | 19/09/2025             |

Cada commit refleja el trabajo colaborativo y el cumplimiento de los objetivos del Sprint, asegurando la trazabilidad y transparencia en el desarrollo de CultiConnection.

**Reporte de commits:**
![Commits](assets/commits.png)

---

#### 5.2.1.5. Execution Evidence for Sprint Review.

En esta entrega, nos centramos en el desarrollo completo de la Landing Page para nuestra plataforma de educación en línea. Nuestro objetivo es desplegar una página web atractiva y efectiva que actúe como el punto de entrada para nuestros usuarios. 

Es por ello que se comparte las evidencias de ambos repositorios para corroborar el trabajo hecho por cada uno de los participantes.

![NetworkGraph](assets/networkgraph.png)


#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Para esta primera entrega no hubo implementación de APIs, pues solo se realizó la Landing Page.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

El objetivo del primer Sprint fue el desarrollo e implementación de la Landing Page. Para eso, utilizamos GitHub y GitHub Pages. El proceso del desarrollo fue el siguiente:

1. Se creó una organización en GitHub y, dentro de ella, se crearon dos repositorios. Uno para el informe del trabajo y otro para la Landing Page ![GithubOrg](assets/organization.png)
2. Luego, a través de los commits, el equipo fue editando los archivos index.html y styles.css, además de ir añadiendo imágenes a utilizar en el directorio images. ![Commits-example](assets/commits-example.png)
3. Finalmente, se implementó GitHub Pages en el repositorio de GitHub y se desplegó la Landing Page, la que se puede visitar en el siguiente link: https://apps-web-grupo-4-frutech.github.io/Landing-Page/

#### 5.2.1.8. Team Collaboration Insights during Sprint.

A continuación, se adjuntan las capturas de evidencia de los insights de los repositorios del informe y Landing Page para evidenciar la participación de todos los miembros:

- Insight Landing Page:
![InsightLP](assets/insightLP.png)

- Insight Report
![InsightR](assets/insightR.png)

## Conclusiones

- El desarrollo del proyecto CultiConnection ha permitido establecer una base sólida para la implementación, validación y despliegue de la aplicación de gestión de alquiler de vehículos. A través de este proceso, se han logrado los siguientes resultados clave:

- La configuración del entorno de desarrollo ha sido fundamental para el éxito del proyecto. La implementación de GitHub como plataforma principal de gestión de código fuente, junto con herramientas complementarias como Trello para la gestión de tareas y Figma para el diseño UX/UI, ha facilitado la colaboración efectiva entre los miembros del equipo. La adopción de tecnologías web estándar (HTML, CSS, JavaScript, Vue.js) y Node.js ha proporcionado una base tecnológica robusta y escalable.

- El Sprint 1 ha demostrado la efectividad de la metodología ágil en el desarrollo del proyecto. La implementación exitosa de la landing page con funcionalidades básicas de registro e inicio de sesión, navegación responsive y diseño atractivo, ha establecido una base sólida para el desarrollo futuro de la aplicación.

- La matriz de liderazgo y colaboración (LACX) ha sido instrumental en la organización del equipo, permitiendo una distribución clara de responsabilidades mientras se mantiene la colaboración entre todos los miembros. 

## 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 2


| Elemento                        | Detalle                                                                                       |
|----------------------------------|----------------------------------------------------------------------------------------------|
| **Sprint**                      | 2 - Implementación de componentes, bounded context, db.json y enrutamiento de Frontend Web Application                 |
| **Sprint Planning Background**   |                                                                                              |
| **Fecha**                       | 9/10/2025                                                                                   |
| **Hora**                        | 23:00 horas (GMT-5)                                                                          |
| **Lugar**                       | Reunión virtual mediante Meet                                                              |
| **Preparado por**               | [FruTech]                                                       |
| **Asistentes**                  | [ Samuel Bonifacio , Jefferson Castro, Bruce Via, Sergio Landa, Estefano Solis ]                                                             |
| **Sprint n-2 Review**           | Se creó el entorno del Frontend Web Application con Vue y Javascript. Se implementó la primera versión de db.json y confiuración de enrutamiento. |
| **Sprint n-2 Retrospective**    | Se implementaron los componentes en el contexto de CultiConnection usando DDD.      |
| **Sprint Goal & User Stories**  |                                                                                              |
| **Sprint 2 Velocity**           | 42 puntos                                                                                    |
| **Sum of Story Points**         | 42 puntos                                                                                    |

#### Objetivo del Sprint
Implementar los componentes principales de la aplicación, establecer el contexto delimitado (bounded context), configurar la base de datos inicial (db.json) y definir el enrutamiento para la navegación en la aplicación web frontend de CultiConnection.

#### User Stories seleccionadas para el Sprint 2

| ID  | User Story                                                                                  | Puntos |
|-----|---------------------------------------------------------------------------------------------|--------|
| 1   | Como usuario, quiero poder registrarme en la aplicación web para acceder a sus funciones.    |   5    |
| 2   | Como usuario, quiero iniciar sesión para acceder a mi cuenta y gestionar mis cultivos.       |   5    |
| 3   | Como usuario, quiero recuperar la contraseña de mi cuenta en caso de olvido.                 |   4    |
| 4   | Como usuario, quiero modificar mi perfil para mantenerlo actualizado.                        |   4    |
| 5   | Como agricultor, quiero registrar diferentes cultivos para mantener un registro a mi alcance.|   5    |
| 6   | Como agricultor, quiero eliminar los cultivos que desee para mantener un registro actualizado.|   4    |
| 7   | Como agricultor, quiero editar los cultivos registrados para asegurarme que estén actualizados.|   4    |
| 8   | Como administrador, quiero verificar y gestionar a los usuarios registrados.                 |   4    |
| 9   | Como administrador, quiero asegurar el acceso al perfil de los usuarios para mantener su información segura.|   4    |
| 10  | Como agricultor, quiero acceder a un historial de los cambios del cultivo para mantener un registro detallado.|   3    |

**Total de puntos:** 42

### 5.2.2.2. Aspect Leaders and Collaborators

En esta sección se presenta la matriz de liderazgo y colaboración (Leadership-and-Collaboration Matrix, LACX) para el Sprint 2 de CultiConnection. Esta matriz identifica, para cada aspecto clave del Sprint, quién es el líder responsable y quiénes son los colaboradores, facilitando así la comunicación y la asignación de tareas dentro del equipo. 

Los aspectos considerados en este Sprint incluyen: diseño de la landing page, desarrollo de funcionalidades de registro e inicio de sesión, implementación de la barra de navegación, y configuración del footer con enlaces de contacto y redes sociales.

| Team Member (Apellido, Nombre)         | GitHub Username      | db.json | Vue Project Setup | BC (Task & Community) | BC (Crops, Dashboard & Fields) |
|----------------------------------------|----------------------|---------------------|--------------------------|---------------------|------------------------|
| Bonifacio, Samuel                     | samuelbonifacio015      | L                   | L                       | L                   | L                      |
| Castro, Jefferson                      | JeffersonCastroPariona     | C                   | L                        | C                   | C                      |
| Via, Bruce                             | Shukaritas            | L                   | L                        | L                   | L                      |                     |
| Solis, Estefano                        | Estefano-Solis-C       | L                   | L                        | L                   | L                      |
| Landa, Sergio                        | Serkekes2006       | C                   | C                        | C                   | C                      |

**L:** Leader (Líder)  
**C:** Collaborator (Colaborador)

Esta organización permite una asignación clara de responsabilidades y fomenta la colaboración efectiva durante el desarrollo del Sprint 2.

### 5.2.2.3. Sprint Backlog 2

| ID   | Title/Section                | Description                                                                                      | Estimation (Hours) | Assigned To                | Status         |
|------|------------------------------|--------------------------------------------------------------------------------------------------|--------------------|----------------------------|---------------|
| US01 | Registro de Usuario          | Implementación del formulario y lógica para el registro de usuarios en la aplicación web.        | 4                  | Samuel Bonifacio           | To-do         |
| US02 | Inicio de Sesión             | Desarrollo del formulario y lógica para el inicio de sesión y gestión de cultivos.               | 4                  | Jefferson Castro           | To-do         |
| US03 | Recuperar Contraseña         | Implementación de la funcionalidad para recuperar la contraseña de usuario.                      | 3                  | Bruce Via                  | To-do         |
| US04 | Editar Perfil                | Desarrollo de la funcionalidad para modificar el perfil del usuario.                             | 3                  | Estefano Solis             | To-do         |
| US05 | Registrar Cultivos           | Implementación del registro de diferentes cultivos por parte del agricultor.                     | 4                  | Samuel Bonifacio           | To-do         |
| US06 | Eliminar Cultivos            | Desarrollo de la funcionalidad para eliminar cultivos registrados.                               | 3                  | Jefferson Castro           | To-do         |
| US07 | Editar Cultivos              | Implementación de la edición de cultivos registrados.                                            | 3                  | Bruce Via                  | To-do         |
| US08 | Gestionar Usuarios           | Desarrollo de la funcionalidad para que el administrador gestione usuarios registrados.          | 3                  | Estefano Solis             | To-do         |
| US09 | Bloqueo de Cuenta            | Implementación de la seguridad para el acceso al perfil de los usuarios.                         | 3                  | Sergio Landa               | To-do         |
| US10 | Historial de Cambios         | Desarrollo de la funcionalidad para acceder al historial de cambios de los cultivos.             | 2                  | Samuel Bonifacio           | To-do         |

**Leyenda de Status:**  
To-do / InProcess / ToReview / Done

---

### 5.2.2.4. Development Evidence for Sprint Review

| Commit ID | Commit Message | User | Commit Date |
| :--- | :--- | :--- | :--- |
| `3c7acf2` | [cite_start]Update index.js [cite: 18] | [cite_start]Shukaritas [cite: 21] | Oct 10, 2025 [cite: 17] |
| `29eae95` | feature: final commit [cite: 22] | [cite_start]Shukaritas [cite: 25] | [cite_start]Oct 10, 2025 [cite: 17] |
| `2db80c7` | commits: preview final changes [cite: 27] | [cite_start]Shukaritas [cite: 30] | [cite_start]Oct 9, 2025 [cite: 26] |
| `683228` | [cite_start]Merge remote-tracking branch 'origin/main' into develop [cite: 31] | [cite_start]Shukaritas [cite: 33] | [cite_start]Oct 9, 2025 [cite: 26] |
| `c9cab99` | [cite_start]Update db.json [cite: 34] | [cite_start]Shukaritas [cite: 37] | [cite_start]Oct 9, 2025 [cite: 26] |
| `41d8990` | fixed db.json [cite: 39] | [cite_start]Estefano-Solis-C [cite: 42] | [cite_start]Oct 8, 2025 [cite: 38] |
| `aeaa6f0` | [cite_start]Merge remote-tracking branch 'origin/feature/fields' into develop [cite: 43] | [cite_start]Estefano-Solis-C [cite: 46] | [cite_start]Oct 8, 2025 [cite: 38] |
| `5167129` | [cite_start]Merge remote-tracking branch 'origin/tasks&comunity' into develop [cite: 51] | [cite_start]Estefano-Solis-C [cite: 53] | [cite_start]Oct 8, 2025 [cite: 38] |
| `e82e591` | [cite_start]Merge remote-tracking branch 'origin/feature/crops' into develop [cite: 54] | [cite_start]Estefano-Solis-C [cite: 57] | [cite_start]Oct 8, 2025 [cite: 38] |
| `f04a0be` | fixture dashboard [cite: 58] | [cite_start]Serkekes2006 [cite: 60] | [cite_start]Oct 8, 2025 [cite: 38] |
| `fa78823` | [cite_start]Add crop registration managment form [cite: 61] | [cite_start]Jefferson CastroPariona [cite: 63] | [cite_start]Oct 8, 2025 [cite: 38] |
| `d1ebf4b` | feat: community API response working [cite: 64] [cite_start]| samuelbonifacio015 [cite: 66] | [cite_start]Oct 8, 2025 [cite: 38] |
| `cf67542` | feat: added community components [cite: 67] [cite_start]| samuelbonifacio015 [cite: 70] | [cite_start]Oct 8, 2025 [cite: 38] |
| `f6766dd` | fix: update task handling [cite: 71] [cite_start]| samuelbonifacio015 [cite: 74] | [cite_start]Oct 8, 2025 [cite: 38] |
| `40b8f5d` | fix: component lang & better comments [cite: 75] [cite_start]| samuelbonifacio015 [cite: 77] | [cite_start]Oct 8, 2025 [cite: 38] |
|`3c134a3` | feat: added my-task component [cite: 78] [cite_start]| samuelbonifacio015 [cite: 80] | [cite_start]Oct 8, 2025 [cite: 38] |
|`245bee2` | feature: Modified and improve fields [cite: 81] | [cite_start]Shukaritas [cite: 84] | [cite_start]Oct 8, 2025 [cite: 38] |
| `c4bde32` | [cite_start]First update [cite: 89] | [cite_start]Estefano-Solis-C [cite: 93] | [cite_start]Oct 7, 2025 [cite: 85] |
| `e41ab39` | [cite_start]Initial commit [cite: 95] | [cite_start]Estefano-Solis-C [cite: 99] | [cite_start]Sep 14, 2025 [cite: 94] |

### 5.2.2.5. Execution Evidence for Sprint Review
- US01

![US01](assets/execution_evidence/Register.jpeg)
<br>
- US02

![US02](assets/execution_evidence/Log_in.jpeg)
<br>
- US04

![US04](assets/execution_evidence/Profile.png)
<br>
- US05

![US05](assets/execution_evidence/Register_Crop.png)
<br>
- US06

![US06](assets/execution_evidence/Delete_Crop.png)
<br>
- US07

![US07](assets/execution_evidence/Edit_crop.png)

### 5.2.2.6. Services Documentation Evidence for Sprint Review

En este Sprint, el enfoque principal ha sido el desarrollo completo del FrontEnd, registro de cultivos, campos y el manejo de informacion de estos. Debido a que aún no se ha implementado un backend ni servicios web, no se cuenta con endpoints
documentados ni documentación OpenAPI en esta fase. <br>
La prioridad fue lograr una experiencia de usuario funcional desde el cliente. En futuras iteraciones se documentarán las
rutas necesarias para la gestión de campos en tiempo real con su informacion, usando OpenAPI como herramienta de especificación.

----
**GitHub Proyecto CultivApp Web Service (Planeado para sprint 3)**
> URL estimada del repositorio del backend (Sprint 3) <br>
>https://github.com/Apps-Web-Grupo-4-FruTech/Backend-AgriApp

### 5.2.2.7. Software Deployment Evidence for Sprint Review
Durante este Sprint, se realizó el despliegue del frontend del sistema CultivApp, incluyendo la Landing Page, el dashboard principal junto con sus secciones principales para el nuestros usuarios, lo cual permitió acceder
fácilmente al desarrollo desde cualquier navegador, facilitando las pruebas funcionales, demostraciones internas y la
recolección de feedback en tiempo real.

![Repositorio_FrontEnd](assets/front-end.png)

- URL del repositorio: https://github.com/Apps-Web-Grupo-4-FruTech/Frontend-FruTech

> URL del despliegue <br>
> https://frontend-frutech-static.onrender.com/

**Responsable**

**- Estefano Sebastian Solis Campos:** Configuracion principal del repositorio, estructura de despliegue


### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, la totalidad del trabajo de implementación fue realizada por todo el equipo, quienes asumimos todas
las funciones de diseño, codificación, validación y despliegue de la solución.

| Integrante  | Acciones realizadas durante el Sprint 2                                    |
|-----|---------------------------------------------------------------------------------------------|
| Estefano Sebastian Solis Campos   | Desarrollo de la interfaz principal, rutas y perfil de usuario  |
| Bruce Via Luna   | Desarrollo de la seccion "My Fields" con sus funcionalidades                  |
| Samuel Jesus Bonifacio Jaramillo   | Desarrollo de la seccion "My Tasks" "Community" con sus funcionalidades y fusion con el landing page     |
| Jefferson Ernesto Castro Pariona   | Desarrollo de la seccion "My Crops" con sus funcionalidades   |
| Sergio Javier Landa Ortiz   | Desarrollo de la seccion "Dashboard" con sus funcionalidades         |

<br>

![Commits_Sprint_2](assets/commits_sprint2.png)

## 5.2.4. Sprint 4

### 5.2.4.1.Sprint Planning 4.

| Elemento | Detalle |
|-----------|----------|
| **Sprint** | 4 - Despliegue de Backend y Frontend con conexión funcional |
| **Sprint Planning Background** |  |
| **Fecha** | 2/12/2025 |
| **Hora** | 20:00 horas (GMT-5) |
| **Lugar** | Reunión virtual mediante Google Meet |
| **Preparado por** | [FruTech] |
| **Asistentes** | [ Samuel Bonifacio , Jefferson Castro, Bruce Via, Estefano Solis, Sergio Landa ] |
| **Sprint n-4 Review** | Se desplegó el backend y frontend nuevamente con la conexión necesario y documentación respectivo  |
| **Sprint n-4 Retrospective** | Positivo: Mayor madurez del backend y mejor comprensión del flujo completo entre frontend–API.<br></br> A mejorar: Coordinar mejor los horarios de trabajo para evitar retrasos en las pruebas. <br></br>Acción: Implementar autenticación en el backend y Alinear endpoints finales con el frontend|
| **Sprint Goal & User Stories** | Consolidar la integración del frontend con la API real, perfeccionar los módulos CRUD implementados, estabilizar la comunicación completa entre vistas y backend, y dejar lista la base para implementar autenticación. |
| **Sprint 4 Velocity** | 16 Story Points |
| **Sum of Story Points** | 16 |

#### Objetivo del Sprint
Desplegar el backend y frontend de CultivApp con una conexión funcional entre ambos, asegurando que los usuarios puedan interactuar con la aplicación de manera efectiva.

### 5.2.4.2. Aspect Leaders and Collaborators.

| Team Member (Apellido, Nombre) | GitHub Username | Deploy de Frontend | Deploy de Backend | Conexión de Endpoints | Documentación de Servicios | Pruebas de Integración |
|--------------------------------|------------------|-------------------------|---------------------|---------------------|-------|----------------------|
| Bonifacio, Samuel | samuelbonifacio015 | C | C | C| L | L |
| Castro, Jefferson | JeffersonCastroPariona | C | C | L | L | L |
| Landa, Sergio | Serkekes2006 | C | C | L | C | L |
| Solis, Estefano | Estefano-Solis-C | L | C | C | C | C |
| Via, Bruce | Shukaritas | L | L| L | C | C |

**L:** Leader (Líder)  
**C:** Collaborator (Colaborador)

---
### 5.2.4.3.Sprint Backlog 4.

### Sprint Backlog 4: Finalización de Backend API

| **User Story** | | **Work-Item / Task (Implementación Backend)** | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Est. (h)** | **Assigned To** | **Status** |
| **US-01** | Registro y Auth | T-101 | Security & JWT Implementation | Implementar generación de Tokens, encriptación de contraseñas (BCrypt) y Middleware de autorización. | 5h | Estefano-Solis-C | Done |
| **US-04** | Editar Perfil | T-102 | User Profile Update Logic | Endpoint PUT para actualizar datos del usuario. Incluye validación de unicidad de correo. | 3h | Estefano-Solis-C | Done |
| **US-12** | Recomendaciones (Comunidad) | T-103 | Community Context Implementation | Desarrollo del Bounded Context `CommunityRecommendation` (visible en carpetas) para lógica de consejos expertos. | 6h | Samuel Bonifacio | To-Review |
| **US-08** | Registro de Campo | T-201 | Fields CRUD Implementation | Implementar `FieldsController` y `FieldRepository` para crear y listar los terrenos del usuario. | 4h | Shukaritas | Done |
| **US-05** | Registrar Cultivos | T-202 | CropFields Logic & Entity | Desarrollo de la entidad central `Crop` y su persistencia en base de datos. | 4h | Shukaritas | Done |
| **US-10** | Vincular Cultivos | T-203 | Relationship Logic (Field-Crop) | Lógica de negocio para asignar un Cultivo existente a un Campo específico (Relación 1:N en BD). | 5h | Shukaritas | Done |
| **US-06** | Eliminar/Editar Cultivos | T-204 | Crop Lifecycle Endpoints | Endpoints DELETE y PUT para gestión de cultivos. Incluye "Soft Delete" (marcar como inactivo en vez de borrar). | 3h | Shukaritas | To-Review |
| **US-13** | Notificación Riego | T-301 | Task Generation Service | Servicio de dominio que calcula automáticamente las tareas de riego basadas en el tipo de cultivo. | 5h | JeffersonCastroPariona | Done |
| **US-17** | Historial Cambios | T-302 | Audit/History Logging | Implementar lógica en `Tasks` para guardar un log cada vez que se completa o modifica una tarea. | 4h | JeffersonCastroPariona | Done |
| **US-11** | Señalaciones | T-303 | Alerts & Signals Endpoint | API para enviar "flags" o alertas al frontend si una tarea (Task) está vencida. | 3h | JeffersonCastroPariona | Done |
| **Global** | Integración | T-400 | Swagger & Documentation | Configuración final de Swagger UI para que el equipo de Frontend pueda probar los endpoints. | 2h | Estefano-Solis-C | Done |


### 5.2.4.4. Development Evidence for Sprint Review

A continuación se presenta la evidencia de desarrollo del Sprint 4, ordenada según la tabla solicitada:

* Commits en Backend: 

| Commit ID  | Commit Message                              | User                     | Commit Date    |
|:----------:|:--------------------------------------------|:------------------------|:--------------|
| 752db64    | feat: add CR REST interfaces                | samuelbonifacio015      | Nov 14, 2025  |
| 36025ed    | feat: add CR infrastructure                 | samuelbonifacio015      | Nov 14, 2025  |
| a3671db    | feat: add CR repositories & services        | samuelbonifacio015      | Nov 14, 2025  |
| d9df421    | feat: CR domain update                      | samuelbonifacio015      | Nov 14, 2025  |
| 4eab47b    | Update Tasks JeffersonCastro                | JeffersonCastroPariona  | Nov 14, 2025  |
| aca777f    | feat: endpoint user and upcoming task       | Gaftherman              | Nov 14, 2025  |
| eefbf08    | feat: pre-deploy                            | Shukaritas              | Nov 14, 2025  |
| 06da246    | Disable forced port                         | Estefano-Solis-C        | Nov 14, 2025  |
| 92a8d2c    | Enabled all ports in all context            | Estefano-Solis-C        | Nov 14, 2025  |
| 82af78e    | Dockerfile                                  | Estefano-Solis-C        | Nov 14, 2025  |
| ed54d60    | feat-updated-bakend                         | Serkekes2006            | Nov 14, 2025  |
| f04a0be    | fixture dashboard 

* Commits en Frontend: 

| Commit ID  | Commit Message                              | User                     | Commit Date    |
|:----------:|:--------------------------------------------|:------------------------|:--------------|
| fa78823    | Add crop registration managment form        | JeffersonCastroPariona  | Oct 8, 2025   |
| d1ebf4b    | feat: community API response working        | samuelbonifacio015      | Oct 8, 2025   |
| cf67542    | feat: added community components            | samuelbonifacio015      | Oct 8, 2025   |
| f6766dd    | fix: update task handling                   | samuelbonifacio015      | Oct 8, 2025   |
| 40b8f5d    | fix: component lang & better comments       | samuelbonifacio015      | Oct 8, 2025   |
| 3c134a3    | feat: added my-task component               | samuelbonifacio015      | Oct 8, 2025   |
| 245bee2    | feature: Modified and improve fields        | Shukaritas              | Oct 8, 2025   |
| 41d8990    | fixed db.json                               | Estefano-Solis-C        | Oct 8, 2025   |
| aeaa6f0    | Merge remote-tracking branch 'origin/feature/fields' into develop | Estefano-Solis-C | Oct 8, 2025   |
| 5167129    | Merge remote-tracking branch 'origin/tasks&comunity' into develop | Estefano-Solis-C | Oct 8, 2025   |


### 5.2.4.5.Execution Evidence for Sprint Review.

En esta entrega nos centramos en el despliegue completo del backend y frontend de la aplicación CultivApp, asegurando una conexión funcional entre ambos.

Es por ello que se comparte las evidencias de ambos repositorios para corroborar el trabajo hecho por cada uno de los participantes.

![NetworkGraphFront](assets/network_graph_front.png)
![NetworkGraphBack](assets/network_graph_back.png)

### 5.2.4.6. Services Documentation Evidence for Sprint Review

En esta sección se incluye la relación de endpoints documentados con OpenAPI (Swagger), desarrollados como parte del alcance del Sprint 4. Se resumen los logros alcanzados en relación con la implementación y documentación de los servicios REST del Backend.

**Backend en Rider**

![RiderBackend](/assets/riderBackend.png)
![RiderBackend2](/assets/riderBackend2.png)

**Frontend en WebStorm**

![WebStormFrontend](/assets/webstormFrontend.png)
![WebStormFrontend2](/assets/webstormFrontend2.png)

**API**

Todos los endpoints están organizados siguiendo la convención RESTful bajo la ruta /api/v1/ y están documentados según
contexto.

<br>

**CultivApp Intern Logic**

|Tag|HTTTP Verb|Endpoint|Summary|Operation ID|
|---|----------|--------|-------|------------|
| AgroApp | GET | / | CultivApp Logic | welcome |

 **Community Recommendations Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|CommunityRecommendation|GET|/api/v1/community-recommendation/{recommendationId}|Get Community Recommendation By Id|GetCommunityRecommendationById|
|CommunityRecommendation|GET|/api/v1/community-recommendation|Get All Community Recommendations|GetAllCommunityRecommendations|
|CommunityRecommendation|PUT|/api/v1/community-recommendation/{id}|Update Community Recommendation|UpdateCommunityRecommendation|

 **CropFields Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|CropFields|POST|/api/v1/crop-fields|Creates a new CropField associated with a Field (1:1 relationship)|CreateCropField|
|CropFields|GET|/api/v1/crop-fields|Gets all CropFields|GetAllCropFields|
|CropFields|GET|/api/v1/crop-fields/{id}|Gets a CropField by ID|GetCropFieldById|
|CropFields|GET|/api/v1/crop-fields/field/{fieldId}|Gets the CropField associated with a Field (1:1 relationship)|GetCropFieldByFieldId|
|CropFields|PUT|/api/v1/crop-fields/{id}|Updates the crop attribute of a CropField|UpdateCropField|

 **Fields Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|Fields|POST|/api/v1/fields|Creates a new field and its associated ProgressHistory automatically|CreateField|
|Fields|GET|/api/v1/fields/user/{userId}|Gets all fields for a user|GetFieldsByUserId|
|Fields|GET|/api/v1/fields/{id}|Gets a field by ID|GetFieldById|

 **Progress History Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|ProgressHistory|GET|/api/v1/progress|Gets all progress history records|GetAll|
|ProgressHistory|POST|/api/v1/progress|Creates a new progress history record|Create|
|ProgressHistory|GET|/api/v1/progress/{id}|Gets a progress history record by ID|GetById|
|ProgressHistory|PUT|/api/v1/progress/{id}|Updates a progress history record|Update|

 **Tasks Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|Tasks|GET|/api/tasks|Gets all registered tasks|GetAllTasks|
|Tasks|POST|/api/tasks|Creates a new task|CreateTask|
|Tasks|GET|/api/tasks/{id}|Gets a specific task by its identifier|GetTaskById|
|Tasks|GET|/api/tasks/field/{fieldId}|Gets tasks associated with a specific field|GetTasksByField|
|Tasks|PUT|/api/tasks/{id}|Updates data of an existing task|UpdateTask|
|Tasks|DELETE|/api/tasks/{id}|Deletes a task|DeleteTask|

 **Users Controller**

|Tag|HTTP Verb|Endpoint|Summary|Operation ID|
|---|---------|--------|-------|------------|
|Users|POST|/api/v1/users/sign-up|Creates a new user in the system|SignUp|
|Users|POST|/api/v1/users/sign-in|Authenticates a user and returns basic session information|SignIn|
|Users|GET|/api/v1/users/{id}|Gets a user by ID|GetById|
|Users|PUT|/api/v1/users/{id}/profile|Updates the profile information of an existing user|UpdateProfile|
|Users|PUT|/api/v1/users/{id}/password|Updates a user's password|UpdatePassword|
|Users|DELETE|/api/v1/users/{id}|Deletes a user from the system|Delete|


### 5.2.4.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 4, se logró desplegar exitosamente la API del Backend y el Frontend del proyecto CultivApp permitiendo el acceso público a los endpoints implementados y documentados.

Esta acción asegura que las funcionalidades desarrolladas estén accesibles para pruebas externas y validación del producto en un entorno de staging.

El despliegue incluye una instancia de servidor corriendo la aplicación .NET y una base de datos MySQL desplegada. 

Finalmente, luego de fusionar correctamente los metodos, se re-desplegó el frontend.

Archivos de configuracion clave

* Dockerfile: Utilizado para construir la imagen personalizada de la aplicación y facilitar el despliegue en Render.

### 5.2.4.8.Team Collaboration Insights during Sprint.
A continuación, se adjuntan las capturas de evidencia de los insights de los repositorios del informe y Landing Page para evidenciar la participación de todos los miembros:

- Insight Landing Page:
![InsightLP](/assets/insightLP.png)

- Insight Report
![InsightR](/assets/insightR.png)

- Insight Backend
![InsightB](/assets/insightsB.png)

- Insight Frontend
![InsightF](/assets/insightsF.png)

# 5.3. Validation Interviews.

## 5.3.1. Diseño de Entrevistas.

**Preguntas para el Segmento #1: Agricultores de Pequeña Escala**

Estas preguntas se centran en la facilidad de uso, el valor inmediato y la barrera tecnológica, asumiendo que el usuario tiene acceso limitado a la tecnología y un enfoque en la producción familiar.

**Módulo: Primeras Impresiones y Panel de Control (Dashboard)**

- Al ver esta pantalla principal, ¿qué es lo más importante para usted? ¿Ver sus campos, sus tareas o las recomendaciones?

- ¿Le parece útil que la aplicación le muestre "Tareas proximas a vencerse" o "Consejos"? ¿Cómo manejaria este contenido?

- ¿Le parece fácil de entender esta pantalla, o ve demasiada información?

- ¿Qué tan importante es para usted poder cambiar el idioma de la aplicación entre inglés y español?

**Módulo: "Mis Campos" y "Gestionar Cultivos"**

- ¿Usted suele organizar su chacra por "campos" o la ve como una sola unidad?

- Al registrar un nuevo campo, ¿le parece útil añadir una foto, nombre y ubicación? ¿Sabe usted el tamaño exacto de su terreno (en hectáreas o m²)?

- Al ver los detalles de su campo, ¿qué datos le interesan más? ¿El "Tipo de Suelo", la "Luz solar" o la "Frecuencia de riego"? ¿Son datos que usted ya conoce?

- ¿Le ayudaría tener un registro de sus cultivos con sus fechas de siembra y cosecha? ¿Suele anotar esta información en algún lugar?

- La aplicación clasifica sus cultivos como "Saludable", "Atención" o "Crítico". ¿Le parece útil esta clasificación? ¿Qué haría usted si viera un cultivo en estado "Crítico"?

**Módulo: "Mis Tareas"**

- ¿Le gustaría recibir recordatorios en su celular para tareas como regar, fertilizar o revisar sus cultivos?

- ¿Le parece sencillo entrar aquí y marcar una tarea como "completada"?

- ¿Qué tipo de tareas le gustaría que la aplicación le recuerde?

**Módulo: "Comunidad"**

- ¿Usted suele pedir consejos a otros agricultores, vecinos o a un agrónomo?

- En esta sección, otros expertos (como "Científicos de Suelo" o "Especialistas en Riego") dan consejos. ¿Confiaría en estos consejos para aplicarlos en su chacra?

- ¿Le gustaría poder hacer preguntas y que otros agricultores o expertos le respondan?

**Módulo: "Perfil" y Configuración**

- Al crear su perfil, ¿le parece bien ingresar su nombre y número de celular? ¿Se sentiría cómodo ingresando su número de DNI?

**Preguntas para el Segmento #2: Agricultores de Mediana Escala (Comercial)**

Estas preguntas se centran en la eficiencia, la gestión de múltiples parcelas, la organización del trabajo y el valor comercial, asumiendo que el usuario maneja una operación más grande y tecnificada.

**Módulo: Primeras Impresiones y Panel de Control (Dashboard)**

- Al ver el "Panel de Control", ¿la información que se muestra (campos, tareas, recomendaciones) es suficiente para que usted planifique su día de trabajo?

- ¿Qué métrica o dato clave le gustaría ver en este panel que no está presente? (Ej. ¿Precios de mercado, resumen de costos, clima?)

- Vemos que el panel muestra "Tareas Próximas". ¿Esto es más valioso para usted o para sus trabajadores?

**Módulo: "Mis Campos" y "Gestionar Cultivos"**

- ¿Qué tan valioso es para usted poder ver todos sus campos en un mapa o lista, cada uno con su estado de salud (Saludable, Atención, Crítico)?

- Al registrar un nuevo campo, ¿qué tan importante es diferenciar "Ubicación" y "Tamaño del campo" para su gestión?

- En la página de "Detalle del Campo", ¿usa usted datos como "Tipo de Suelo", "frecuencia de riego (en litros)" y "horas de luz solar" para tomar decisiones?

- ¿Le gustaría poder añadir un historial de "Progreso" (riego, fertilización, pestes) más detallado? ¿Quizás con costos asociados?

- Al "Gestionar Cultivos", ¿la vista de tabla es la mejor forma de ver sus cultivos, o preferiría un calendario?

- ¿La información que se pide al registrar un nuevo cultivo (nombre, fechas, campo, estado) es suficiente para su control comercial? ¿Le faltaría registrar "Variedad", "Rendimiento esperado" o "Costo de siembra"?

**Módulo: "Mis Tareas"** 

- ¿Cómo gestiona actualmente las tareas de sus trabajadores? ¿Usa cuadernos, WhatsApp, o algún otro método?

- ¿Usaría esta sección de "Mis Tareas" para organizar el trabajo de su equipo?

- ¿Qué le faltaría a esta sección para serle realmente útil? (Ej. ¿Poder asignar una tarea a un trabajador específico? ¿Marcar una tarea como "Urgente"?)

**Módulo: "Comunidad"**

- ¿De dónde obtiene sus recomendaciones técnicas actualmente (proveedores de insumos, agrónomo privado, juntas de regantes)?

- Esta sección de "Comunidad" ofrece consejos de expertos. ¿Le parecen consejos generales o información técnica valiosa que podría aplicar para mejorar su rentabilidad?

- ¿Preferiría un foro público o un servicio de chat directo para consultar a un "Especialista en Riego" o un "Consultor de Plagas"?

**Módulo: "Perfil" y Configuración**

- En la sección "Perfil", ¿qué tan importante es para usted poder cambiar su contraseña y ver su información personal?

## 5.3.2. Registro de Entrevistas.

## 5.3.2. Evaluaciones según heurísticas.

<span style="font-size: 2em; font-weight: normal;">Site o App a evaluar</span>

**Nombre:** AgroApp

**Objetivo:**  Identificar problemas de usabilidad en el sistema web de control de campos y cultivos usando la Lista Heurística de
Nielsen.

<span style="font-size: 2em; font-weight: normal;">Tareas a evaluar</span>

1. Visualización y navegación en la página principal
2. Visualización del campo de Cultivo (galería, fichas, presentación de información)
3. Navegación por la sección de Cultivos (flujo, claridad de información, pasos a seguir)
4. Accesibilidad y claridad del menú lateral (ubicación, iconos, estructura)
5. Visualizacion de los atributos de los campos y cultivos (nombre, dimensiones, producto, estado, etc)
6. Diferenciación entre las secciones “Cultivos” y “Campos”
7. Visualización de detalles del campo (tareas, estado, producto)
8. Gestión de cultivos y sus campos (tareas, recordatorios)
9. Claridad de iconografía y etiquetas
10. Navegación lateral y localización de sección activa
11. Estructura y claridad del formulario de registros
12. Proceso de cambio de idioma
13. Personalización y curva de aprendizaje

<span style="font-size: 2em; font-weight: normal;">Problema Detectado</span>

| # | Problema Detectado | Heuristica violada | Severidad |
|---|--------------------|--------------------|-----------|
|1|Falta de complementos visuales|Visibilidad del estado del sistema|1|
|2|Confusión entre Campos y Cultivos|Coincidencia entre el sistema y el mundo real|3|
|3|Falta de tutoriales o guía para nuevos usuarios |Ayuda y documentación|2|
|4|Inconsistencia de los estados de los campos|Visibilidad del estado del sistema|3

<span style="font-size: 2em; font-weight: normal;">Escala de severidad</span>

|Nivel |Severidad|
|------|---------|
|1|Problema superficial: fácilmente superado por el usuario o muy poco frecuente. No es prioritario.|
|2|Problema menor: algo más frecuente o confuso; se debe resolver en una próxima versión.|
|3|Problema mayor: ocurre frecuentemente y afecta el uso normal. Prioridad alta.|
|4|Problema muy grave: impide el uso del sistema. Debe corregirse antes del lanzamiento.|

<span style="font-size: 2em; font-weight: normal;">Análisis heuristico detallado</span>

<span style="font-size: 19px; font-weight: normal;">Problema #01: Falta de complementos visuales</span>

**Severidad:** 1

**Heuristica violada:** Visibilidad del estado del sistema

**Descripción:**

Las secciones como cultivos o tareas no se ven atractivas visualmente para los usuarios, o segun ellos le falta algun atratactivo visual

**Recomendación:**

Incluir divisores visuales, algunos colores a los botones y una mejor presentacion de modo que se vuelve atractivo para mas usuarios y deja de parecer una lista impresa

<span style="font-size: 19px; font-weight: normal;">Problema #02: Confusión entre Campos y Cultivos</span>

**Severidad:** 3

**Heuristica violada:** Coincidencia entre el sistema y el mundo real

**Descripción:**

Los usuarios no difrencian muy bien entre las dos secciones, confundiendolas constantement al momento de referirse a estas

**Recomendación:**

Renombrar o cambiar la forma de etiquetar cada una de esas por ejemplos ("Cultivos pertenecientes a un campo" o "Campos de Cultivo")

<span style="font-size: 19px; font-weight: normal;">Problema #03: Falta de tutoriales o guía para nuevos usuarios</span>

**Severidad:** 2

**Heuristica violada:** Ayuda y documentación

**Descripción:**

No hay tutorial, guía ni sección de ayuda visible. Esto afecta la curva de aprendizaje, especialmente en usuarios no expertos

**Recomendación:**

Incluir un recorrido inicial con explicaciones breves, un botón de ayuda permanente o una sección de preguntas frecuentes

<span style="font-size: 19px; font-weight: normal;">Problema #04: Inconsistencia de los estados de los campos</span>

**Severidad:** 3

**Heuristica violada:** Visibilidad del estado del sistema

**Descripción:**

Los usuarios remarcan como lo estados de los campos pese a seguir una guia con los colores, algunos estan en ingles y otros en español, si bien son acorde a lo que se muestra, genera confusion 

**Recomendación:**

Estandarizar todos los estados a un lenguaje u otro, ademas de usar tambien las mismas palabras para que siempre muestren la que quiere representar

## 5.4. Video About-the-Product.

En esta sección, el equipo presenta un resumen de los aspectos más relevantes del video "About The Product –CultivApp". El video muestra en detalle las características principales de la aplicación, enfocándose en cómo cada funcionalidad ha sido diseñada para responder a las necesidades reales de los usuarios interesados en el cuidado de sus cultivos a mayor o menor escala.


A lo largo del video, se presentan demostraciones visuales de la aplicación en funcionamiento, incluyendo flujos clave como la creracion de los campos, la creacion de los cultivos, la vinculacion de estos y la creacion de tareas.

La narración guía al espectador a través de la experiencia del usuario, mientras que testimonios reales aportan valor, reflejando el impacto positivo que CultivApp ha tenido tanto en agricultores pequeños como en agricultores a mayor escala. Estos relatos destacan la facilidad de uso y el beneficiendo y mejorando el cuidado de los agricultores a sus cultivos.

Este video no solo presenta el producto, sino que lo contextualiza como una solución digital efectiva para un problema social, demostrando su utilidad, usabilidad e impacto.

**Cuadro Representativo del Video**

![Commits_Sprint_2](assets/Caputa_About-The-Product_Apps.png)

**Url del video:** https://drive.google.com/file/d/1HbL1P0xfdrvprUTJO9YlcpjOW9l0H1Cg/view?usp=sharing 

## Conclusiones

- Gestión de Entorno y Colaboración Efectiva: La gestión del código fuente a través de GitHub ha sido un pilar para el avance del proyecto, facilitando la colaboración continua entre los miembros del equipo. La constante actividad, evidenciada por los commits de múltiples desarrolladores, demuestra una sinergia de trabajo y una plataforma de desarrollo bien establecida.

- Avance Funcional y Desarrollo Ágil: El progreso reciente demuestra la efectividad del equipo en la integración de funcionalidades clave. Los commits de los últimos días indican avances significativos en módulos como:

- Cohesión Técnica y Organización del Equipo: La integración de estas características, reflejada en los frecuentes merges de ramas de funcionalidad (como feature/fields y feature/crops) hacia una rama principal de desarrollo, sugiere un modelo de trabajo organizado. Este enfoque permite contribuciones en paralelo por parte del equipo, manteniendo la cohesión e integridad del proyecto para futuras iteraciones.

## Bibliografía

1. **GitHub Inc.** (2024). *GitHub: Where the world builds software*. Recuperado de https://github.com/

2. **Node.js Foundation** (2024). *Node.js: JavaScript runtime built on Chrome's V8 JavaScript engine*. Recuperado de https://nodejs.org/

3. **Vue.js Team** (2024). *Vue.js - The Progressive JavaScript Framework*. Recuperado de https://vuejs.org/

4. **Microsoft Corporation** (2024). *Visual Studio Code: Code editing. Redefined*. Recuperado de https://code.visualstudio.com/

5. **JetBrains s.r.o.** (2024). *WebStorm: The smartest JavaScript IDE*. Recuperado de https://www.jetbrains.com/webstorm/

6. **Schwaber, K., & Sutherland, J.** (2020). *The Scrum Guide: The Definitive Guide to Scrum*. Recuperado de https://scrumguides.org/

7. **Beck, K., et al.** (2001). *Manifesto for Agile Software Development*. Recuperado de https://agilemanifesto.org/

8. **Atlassian Corporation** (2024). *Trello: Organize anything, together*. Recuperado de https://trello.com/

9. **Figma Inc.** (2024). *Figma: The collaborative interface design tool*. Recuperado de https://www.figma.com/

10. **Miro** (2024). *Miro: The visual workspace for innovation*. Recuperado de https://miro.com/


## Anexos

[Repositorio de Reporte](https://github.com/Apps-Web-Grupo-4-FruTech)

[Repositorio de LandingPage](https://github.com/Apps-Web-Grupo-4-FruTech/Landing-Page)

[Repositorio de Frontend](https://github.com/Apps-Web-Grupo-4-FruTech/Frontend-FruTech)

[Canvas](https://www.canva.com/design/DAGzlK9YqZs/5TXIxqLG4Ih5yCHLwJacVA/edit?utm_content=DAGzlK9YqZs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
