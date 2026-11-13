# Documentación del Proyecto

## Introducción
Este repositorio reúne las actividades y evidencias desarrolladas durante las diferentes sesiones de trabajo. Su contenido aborda tres aspectos principales: la implementación de algoritmos de programación, el análisis crítico de respuestas generadas por inteligencia artificial y el diseño y desarrollo conceptual de una plataforma web educativa.

El proyecto busca evidenciar tanto los conocimientos técnicos adquiridos como la capacidad de utilizar herramientas de inteligencia artificial para resolver problemas, analizar información, generar propuestas y apoyar procesos de desarrollo de software.

## Estructura del repositorio
El repositorio está organizado en carpetas por sesiones, permitiendo identificar fácilmente las actividades y los archivos correspondientes a cada una.

```text
ia-1/
│
├── sesion-01/
│   └── algoritmo-ordenamiento.py
│
├── sesion-02/
│   └── riwi-tres-cupos-borrador.txt
│
├── sesion-03/
│   └── pagina-ia.md
│
└── README.md
```

## Descripción general

| Ubicación | Archivo | Descripción |
| :--- | :--- | :--- |
| `sesion-01/` | `algoritmo-ordenamiento.py` | Implementación de un algoritmo de ordenamiento en Python. |
| `sesion-02/` | `riwi-tres-cupos-borrador.txt` | Desarrollo de una actividad de selección de estudiantes mediante inteligencia artificial y análisis de sus respuestas. |
| `sesion-03/` | `pagina-ia.md` | Recopilación de requerimientos, decisiones de diseño y proceso de desarrollo de una plataforma educativa utilizando IA. |
| Raíz | `README.md` | Documento principal con la descripción y documentación del repositorio. |

---

## Sesión 01. Algoritmos de programación

**Ubicación:** `sesion-01/algoritmo-ordenamiento.py`

### Descripción
En esta sesión se desarrolló un ejercicio práctico de programación en Python enfocado en el ordenamiento de elementos de una lista.
El archivo contiene una implementación del algoritmo Insertion Sort (ordenamiento por inserción), cuyo objetivo es organizar una colección de números de menor a mayor.

### Funcionamiento
El algoritmo trabaja recorriendo una lista y construyendo progresivamente una sección ordenada.
Su funcionamiento se divide en los siguientes pasos:
1. **Inicialización:** Se define una lista con varios números desordenados.
2. **Recorrido:** Se utiliza un ciclo `for` para recorrer los elementos desde la segunda posición.
3. **Selección:** Se guarda el elemento actual en una variable temporal.
4. **Comparación:** Mediante un ciclo `while`, se comparan los elementos anteriores con el valor seleccionado.
5. **Desplazamiento:** Si un elemento anterior es mayor, se desplaza una posición hacia la derecha.
6. **Inserción:** Cuando se encuentra la posición adecuada, se inserta el elemento seleccionado.
7. **Resultado:** Finalmente, se imprime la lista completamente ordenada.

### Conceptos aplicados
- Listas en Python.
- Variables y asignación de valores.
- Ciclos `for` y `while`.
- Condicionales.
- Índices y posiciones dentro de listas.
- Comparación y desplazamiento de elementos.
- Lógica de algoritmos de ordenamiento.

### Resultado esperado
Al ejecutar el archivo, los números de la lista quedan organizados de forma ascendente.
Este ejercicio permite comprender cómo funcionan los algoritmos de ordenamiento y cómo resolver un problema mediante estructuras de control básicas, sin depender de funciones de ordenamiento incorporadas en Python.

---

## Sesión 02. Uso crítico de inteligencia artificial

**Ubicación:** `sesion-02/riwi-tres-cupos-borrador.txt`

### Descripción
Esta sesión se centró en analizar cómo una inteligencia artificial puede participar en la toma de decisiones cuando existen recursos limitados y diferentes situaciones personales que deben tenerse en cuenta.

La actividad planteó un escenario ficticio en el que ocho estudiantes necesitaban acompañamiento académico, pero solamente existían tres cupos disponibles.
El objetivo no era únicamente seleccionar a los estudiantes con las notas más bajas, sino evaluar sus circunstancias, necesidades y posibilidades de beneficiarse del programa.

### Desarrollo de la actividad

#### 1. Elección individual
Inicialmente se realizó una selección sin intervención de la inteligencia artificial.
Se eligieron Ana, Elena y Hugo, considerando que sus dificultades estaban relacionadas principalmente con aspectos académicos y que podían beneficiarse del acompañamiento.
Esta primera decisión permitió establecer un criterio propio para compararlo posteriormente con las recomendaciones de la IA.

#### 2. Primera consulta a la IA
Se proporcionó a la inteligencia artificial la información de los ocho estudiantes, incluyendo:
- Notas académicas.
- Porcentajes de asistencia.
- Situaciones personales.
- Dificultades identificadas.

Se solicitó seleccionar los tres estudiantes que más necesitaban acompañamiento, justificar cada elección y explicar por qué los demás no habían sido seleccionados.

**Primera propuesta de la IA:**
- Diego.
- Gabriela.
- Camila.

La IA priorizó el riesgo de abandonar el curso, las dificultades externas y las posibilidades de que el acompañamiento generara un cambio positivo.

#### 3. Análisis de la primera respuesta
Después de recibir la recomendación, se identificaron algunos aspectos importantes del razonamiento de la IA.
La herramienta no se limitó a comparar las calificaciones, sino que interpretó las circunstancias de cada estudiante.
Sin embargo, también realizó algunas suposiciones que no estaban respaldadas directamente por la información proporcionada. Por ejemplo, consideró que Gabriela podría recibir acceso a un computador mediante el programa y asumió que Ana ya contaba con suficientes recursos para continuar.
Esto permitió identificar la importancia de revisar las respuestas generadas por IA y no asumir que todas sus conclusiones son correctas.

#### 4. Segunda consulta: incorporación de contexto
Posteriormente se realizó una nueva consulta, agregando información específica sobre el funcionamiento del Programa B: Continuidad en el curso.
Se aclaró que el programa ofrecía:
- Ocho semanas de acompañamiento.
- Tutorías semanales con horarios flexibles.
- Seis horas adicionales de acceso a computadores por semana.
- Disponibilidad de al menos un horario para los ocho estudiantes.

También se especificó que no incluía apoyo económico ni préstamo de computadores para utilizar en casa.
Esta información permitió que la IA evaluara las necesidades de los estudiantes en relación con los beneficios reales del programa.

**Segunda propuesta de la IA:**
- Diego.
- Bruno.
- Gabriela.

#### 5. Comparación de resultados
La principal diferencia entre ambas respuestas fue el cambio de Camila por Bruno.
En la primera consulta, la IA seleccionó a Camila porque presentaba dificultades para resolver ejercicios de manera independiente.
En la segunda consulta, Bruno fue seleccionado porque sus problemas de asistencia estaban relacionados con sus horarios laborales y el programa ofrecía tutorías flexibles.
Por lo tanto, la nueva información modificó el criterio de selección: ya no se trataba solamente de identificar quién necesitaba ayuda, sino de determinar quién podía beneficiarse directamente de los recursos disponibles.

### Conclusiones de la actividad
El ejercicio permitió comprender que la calidad de una respuesta generada por inteligencia artificial depende considerablemente del contexto y de las instrucciones proporcionadas.

Para obtener recomendaciones más acertadas es necesario definir:
1. El objetivo de la decisión.
2. Los recursos y beneficios disponibles.
3. Los criterios de selección.
4. Las limitaciones del programa.
5. La importancia de las circunstancias particulares de cada persona.

También se evidenció que la IA puede interpretar información, establecer prioridades y justificar decisiones, pero sus recomendaciones deben ser revisadas por personas que conozcan el contexto real.

**Aprendizaje principal:** Una misma situación puede producir resultados diferentes dependiendo de la información proporcionada y de los criterios utilizados para analizarla.

---

## Sesión 03. Diseño y desarrollo de una plataforma educativa con IA

**Ubicación:** `sesion-03/pagina-ia.md`  
**Proyecto relacionado:** DevForge

### Descripción
En esta sesión se documentó el proceso de conceptualización, diseño y desarrollo de una plataforma web educativa orientada principalmente a personas que están comenzando en el mundo de la programación.
La propuesta consiste en desarrollar un entorno que reúna diferentes herramientas de aprendizaje y colaboración en un mismo lugar.

Para llevar a cabo el proyecto se utilizó inteligencia artificial como herramienta de apoyo durante las diferentes etapas del desarrollo: desde la generación de ideas iniciales hasta la definición de requisitos técnicos y la implementación de funcionalidades.

El archivo `pagina-ia.md` contiene la recopilación del proceso de trabajo, las decisiones tomadas, los requerimientos establecidos y las instrucciones utilizadas durante las diferentes etapas.

### 1. Conceptualización de la plataforma
Inicialmente se utilizó inteligencia artificial para explorar posibles características de una plataforma educativa enfocada en programación.
Se definió como público principal a estudiantes principiantes y se planteó una plataforma que combinara diferentes espacios de aprendizaje.

Entre las ideas principales se establecieron:
- Cursos de programación.
- Foros comunitarios similares a Reddit.
- Comunicación privada entre estudiantes y tutores.
- Mentorías personalizadas.
- Cursos y contenidos de pago.
- Retos prácticos de programación inspirados en Codewars.

También se definió un modelo de monetización basado en la compra individual de cursos, contemplando una comisión del 10 % para la plataforma.
La IA participó en esta etapa proponiendo alternativas, organizando las ideas y ayudando a identificar funcionalidades que podían complementar la propuesta inicial.

### 2. Definición de identidad visual
Una vez establecida la idea general, se trabajó en la identidad visual de la plataforma.
Se definió una paleta de cinco colores principales:

| Color | Código | Uso |
| :--- | :--- | :--- |
| Slate Dark | `#0F172A` | Fondos principales y superficies oscuras. |
| Indigo Vívido | `#6366F1` | Botones, elementos interactivos y acciones principales. |
| Esmeralda Código | `#10B981` | Estados positivos y elementos relacionados con programación. |
| Rosa Alerta | `#F43F5E` | Alertas, errores y acciones de advertencia. |
| Blanco Nieve | `#F8FAFC` | Textos y elementos de alto contraste. |

También se definieron criterios visuales relacionados con la distribución de los componentes, tipografías, tarjetas, navegación y experiencia de usuario.

### 3. Diseño y maquetación con Stitch
Para construir la propuesta visual se utilizó Stitch como herramienta de diseño asistido por inteligencia artificial.
El proceso consistió en proporcionar instrucciones progresivamente más específicas sobre la estructura y el funcionamiento esperado de la plataforma.

Inicialmente se trabajó en la generación de una propuesta visual general. Posteriormente, se complementaron las instrucciones con aspectos técnicos y funcionales para conseguir una maqueta más completa.

En esta etapa se buscó definir:
- Distribución de las diferentes secciones.
- Navegación entre módulos.
- Componentes visuales.
- Identidad gráfica.
- Experiencia de usuario.
- Estructura general de las páginas.

Una vez generada la propuesta, se exportaron los archivos de diseño para utilizarlos como referencia en la siguiente etapa.

### 4. Definición de requisitos funcionales y no funcionales
Con la estructura visual establecida, se utilizó nuevamente IA para organizar los requisitos de la aplicación.
Se buscó transformar la maqueta en una plataforma que no solamente tuviera una apariencia funcional, sino que también contemplara comportamientos e interacciones reales.

Se trabajaron aspectos como:
- Registro e inicio de sesión.
- Administración de usuarios.
- Gestión de cursos.
- Seguimiento del progreso.
- Sistema de mensajería.
- Interacción en foros.
- Sistema de retos.
- Notificaciones.
- Administración de tutores.
- Persistencia de información.

También se consideraron requisitos técnicos relacionados con seguridad, rendimiento, organización del código, aislamiento de información entre usuarios y escalabilidad.

### 5. Implementación utilizando V0 y tecnologías web
Después de finalizar la etapa de diseño, se utilizó V0 de Vercel como herramienta de generación y desarrollo asistido por IA.
Se proporcionaron los archivos exportados desde Stitch junto con instrucciones que explicaban la arquitectura deseada, las funcionalidades y los comportamientos esperados.

El objetivo fue transformar la maqueta visual en una aplicación web interactiva.
Se definió como base tecnológica:
- **Next.js:** Framework principal para construir la aplicación.
- **App Router:** Sistema de organización de rutas y páginas.
- **TypeScript:** Lenguaje utilizado para desarrollar con tipado estático.
- **Tailwind CSS:** Herramienta para construir y mantener los estilos visuales.

Durante esta etapa se trabajaron diferentes módulos de la plataforma:

#### 5.1. Sistema de diseño
Se buscó mantener una identidad visual consistente en toda la aplicación. Se contemplaron:
- Aplicación de la paleta de colores.
- Tipografías Space Grotesk, Geist y JetBrains Mono.
- Notificaciones Toast.
- Buscador global mediante `Ctrl + K`.
- Estados interactivos.
- Animaciones y mejoras visuales.

#### 5.2. Autenticación y almacenamiento de información
Inicialmente se planteó un sistema de almacenamiento local denominado DevForgeDB, utilizando `localStorage` del navegador. Este sistema simulaba una estructura de base de datos relacional mediante diferentes colecciones de información:
- `users`: Información de los usuarios.
- `user_progress`: Progreso individual de aprendizaje.
- `courses`: Información de los cursos.
- `course_doubts`: Preguntas y dudas sobre los cursos.
- `forum_threads`: Publicaciones del foro.
- `forum_comments`: Comentarios de las publicaciones.
- `direct_messages`: Mensajes privados.
- `notifications`: Notificaciones de los usuarios.

También se definió un sistema de autenticación que restringe el acceso a las secciones privadas de la plataforma. Se contempló la separación de información según el usuario autenticado y la inicialización de estadísticas para nuevos registros.
*Es importante aclarar que localStorage representa una solución de persistencia local y no una base de datos centralizada compartida entre dispositivos.*

#### 5.3. Sistema de evaluación de tutores
Se diseñó un proceso de evaluación técnica para las personas interesadas en registrarse como tutores. La dificultad de la evaluación depende de la tarifa por hora seleccionada:
- **Nivel 1:** entre 10 y 30 USD por hora.
- **Nivel 2:** entre 31 y 60 USD por hora.
- **Nivel 3:** más de 60 USD por hora.

Cada nivel representa una exigencia técnica diferente, desde conocimientos Junior-Mid hasta perfiles Staff/Principal. Al aprobar la evaluación, se contempla la asignación de la insignia *Tutor Verificado* y la habilitación del perfil en el directorio de mentores.

#### 5.4. Panel de administración para tutores
Se planteó un espacio exclusivo para los usuarios que tienen el rol de tutor. Desde este panel se contempla la posibilidad de:
- Administrar cursos.
- Crear módulos y subtemas.
- Agregar contenido teórico en Markdown.
- Incorporar fragmentos de código.
- Consultar el progreso de los estudiantes.
- Revisar las dudas de los aprendices.
- Responder preguntas.

La finalidad es permitir que los tutores administren sus contenidos y acompañen el proceso de aprendizaje de sus estudiantes.

#### 5.5. Sistema de cursos y aprendizaje (LMS)
Se diseñó un reproductor de cursos que organiza el contenido en diferentes niveles. La estructura propuesta contempla tres cursos iniciales:
1. Fundamentos de JavaScript & DOM.
2. React: interfaces que escalan.
3. TypeScript para equipos reales.

Cada curso contiene tres módulos y cada módulo está dividido en tres subtemas. Dentro de las lecciones se contempla contenido teórico, ejemplos de código y ejercicios prácticos. También se definió un sistema de experiencia (XP), que otorga 25 puntos por cada lección completada y actualiza el progreso del estudiante.

#### 5.6. Retos de programación
Se planteó un módulo inspirado en plataformas como Codewars. Su objetivo es permitir que los estudiantes practiquen mediante problemas de programación con diferentes niveles de dificultad.
Se contemplaron los siguientes lenguajes:
- JavaScript.
- TypeScript.
- Python.
- SQL.

Los retos se organizan utilizando niveles de dificultad desde 8 kyu hasta 4 kyu. Entre sus funcionalidades propuestas se encuentran:
- Enunciados de ejercicios.
- Editor de soluciones.
- Casos de prueba.
- Validación de respuestas.
- Consola de resultados.
- Registro de tiempos de ejecución.
- Recompensas de XP.
- Desbloqueo de soluciones compartidas por la comunidad.

*Consideración técnica:* Se identificó que ejecutar código mediante `new Function` en el navegador no constituye un entorno seguro para ejecutar código arbitrario de usuarios. Para una versión de producción se requiere un sistema de ejecución aislado (sandbox).

#### 5.7. Comunidad y foros
Se planteó un espacio comunitario donde los estudiantes puedan compartir conocimientos, realizar preguntas y publicar soluciones. Su funcionamiento toma como referencia los foros tradicionales y plataformas como Reddit.
Se definieron funcionalidades como:
- Crear publicaciones.
- Comentar publicaciones.
- Votar positiva o negativamente.
- Acumular Karma.
- Marcar respuestas como soluciones aceptadas.
- Identificar publicaciones resueltas y sin resolver.
- Filtrar contenido por tendencias, publicaciones recientes y elementos guardados.
- Administrar las publicaciones y comentarios propios.

El objetivo es fomentar la colaboración y permitir que los estudiantes aprendan también mediante la interacción con otros miembros.

#### 5.8. Notificaciones y personalización
Se definió un sistema de notificaciones para informar a los usuarios sobre diferentes acontecimientos dentro de la plataforma. Entre ellos:
- Nuevos mensajes.
- Respuestas de tutores.
- Reservas.
- Actividad relacionada con sus publicaciones.

También se contempló la posibilidad de marcar notificaciones como leídas y no leídas. Adicionalmente, se establecieron preferencias visuales individuales, incluyendo modo oscuro y modo claro.

#### 5.9. Centro de documentación
Se propuso incorporar una sección de documentación para explicar diferentes aspectos de la plataforma. Entre los contenidos considerados se encuentran:
- Documentación oficial.
- Guía del sistema de Karma.
- Explicación de los rangos Kyu.
- Código de conducta.
- Programa de mentores.
- Estado de la plataforma.

### 6. Ampliación del sistema de mensajería
Después de trabajar en las funcionalidades principales, se identificó la necesidad de mejorar el módulo de comunicación privada. Por este motivo, se elaboró una nueva solicitud para ampliar el sistema de mensajes.

La principal mejora consistió en permitir que cualquier usuario autenticado, independientemente de su rol, pudiera iniciar conversaciones con otros usuarios registrados. Se definió un botón denominado *Nuevo Mensaje*, que abre una ventana para buscar personas dentro de la plataforma. El buscador contempla consultas por nombre y correo electrónico, excluyendo al usuario que ha iniciado sesión.

También se estableció un mecanismo para comprobar si ya existe una conversación entre los participantes. Si la conversación existe, se recupera el chat correspondiente. En caso contrario, se crea una nueva conversación y se actualiza el estado de la aplicación. Esta ampliación buscó mejorar la comunicación entre aprendices y tutores, evitando que los usuarios dependieran de conversaciones creadas previamente.

### 7. Propuesta de migración a infraestructura en la nube
En una etapa posterior se identificaron las limitaciones del almacenamiento local. Al utilizar `localStorage`, la información se mantiene en el navegador donde se genera, lo que dificulta compartir datos entre diferentes dispositivos y usuarios.

Por esta razón, se trabajó en una nueva propuesta para migrar la infraestructura hacia una base de datos en la nube. Se contemplaron dos alternativas tecnológicas:
- Supabase con PostgreSQL.
- Firebase con Firestore.

La propuesta busca centralizar la información de los usuarios, cursos, progreso, publicaciones, comentarios, mensajes y notificaciones. También se planteó implementar:
- Autenticación centralizada.
- Sesiones persistentes.
- Tokens JWT.
- Control de roles y permisos.
- Sincronización de publicaciones en tiempo real.
- Actualización inmediata de mensajes.
- Notificaciones en tiempo real.
- Indicadores del estado de conexión.

**Estado de esta etapa**
> **IMPORTANTE:** La migración a infraestructura en la nube está pendiente de finalización. La solicitud de implementación se proporcionó a V0, pero no pudo completarse debido a una limitación de tokens de la herramienta. Por lo tanto, esta etapa debe considerarse una propuesta técnica en proceso y no una funcionalidad terminada.

Para completar la migración es necesario:
1. Configurar el proveedor de base de datos.
2. Crear y migrar el esquema de información.
3. Configurar el sistema de autenticación.
4. Establecer políticas de seguridad y permisos.
5. Implementar las suscripciones en tiempo real.
6. Migrar los datos existentes.
7. Realizar pruebas con diferentes usuarios y dispositivos.

### 8. Metodología de trabajo con inteligencia artificial
Uno de los aspectos más importantes de esta sesión fue el uso de inteligencia artificial durante las diferentes etapas de desarrollo. En lugar de utilizar una única instrucción para generar toda la aplicación, se trabajó mediante un proceso iterativo en el que cada solicitud tenía un objetivo específico.

La metodología aplicada fue la siguiente:
1. **Exploración de ideas:** Se utilizó IA para analizar posibilidades, identificar funcionalidades y definir el público objetivo de la plataforma.
2. **Definición de requerimientos:** Se transformaron las ideas iniciales en características funcionales y técnicas más concretas.
3. **Diseño visual:** Se utilizaron herramientas de generación asistida para construir la propuesta visual y establecer una identidad gráfica.
4. **Generación de la aplicación:** Se proporcionaron a V0 los archivos de diseño y las especificaciones necesarias para convertir la maqueta en una aplicación interactiva.
5. **Ampliación de funcionalidades:** Se realizaron nuevas consultas para mejorar módulos específicos, como la mensajería y la administración de usuarios.
6. **Evolución de la arquitectura:** Finalmente, se planteó una migración desde el almacenamiento local hacia una infraestructura centralizada en la nube.

Durante todo el proceso, las instrucciones se fueron ajustando según los resultados obtenidos y las necesidades que aparecieron. Esto permitió trabajar de manera progresiva, evitando intentar desarrollar todas las funcionalidades en una sola solicitud. También se utilizaron criterios técnicos para orientar las respuestas de la IA, como las tecnologías que debía emplear, la estructura de los módulos, los comportamientos esperados y las limitaciones que debía tener en cuenta.

### 9. Conclusiones de la sesión
El desarrollo de DevForge permitió explorar cómo la inteligencia artificial puede apoyar la creación de software, desde la conceptualización hasta la generación de componentes y funcionalidades.

También permitió comprender que generar una aplicación mediante IA no significa que todo el sistema esté automáticamente terminado o sea apto para producción. Es necesario revisar el código generado, comprobar que las funcionalidades trabajen correctamente, validar la seguridad y verificar que la arquitectura responda a las necesidades reales del proyecto.

Uno de los principales aprendizajes fue la importancia de proporcionar instrucciones claras, dividir los problemas en tareas pequeñas y mantener un proceso de revisión constante.

---

## Conclusión general del repositorio

Las tres sesiones representan diferentes formas de aplicar conocimientos de programación y herramientas de inteligencia artificial.
- **Sesión 01:** Aplicación de fundamentos de programación mediante la implementación de un algoritmo de ordenamiento en Python.
- **Sesión 02:** Análisis del comportamiento de la inteligencia artificial ante un problema de toma de decisiones, evaluando la importancia del contexto y la calidad de las instrucciones.
- **Sesión 03:** Utilización de inteligencia artificial como herramienta de apoyo para conceptualizar, diseñar y desarrollar una plataforma web educativa.

En conjunto, el trabajo demuestra que la IA puede facilitar procesos de aprendizaje, análisis y desarrollo tecnológico. Sin embargo, su utilización requiere criterio humano, validación de resultados y comprensión de los procesos que se están realizando.

La inteligencia artificial funciona como una herramienta de apoyo, mientras que la definición de objetivos, la evaluación de resultados y las decisiones finales siguen dependiendo del criterio de las personas que desarrollan el proyecto.

## Promt utilizado

```text
Te voy a compartir la estructura de un trabajo con su contenido necesito que me ayudes a documentar todo el contenido en el readme.md. 

Especifica que hace cada cosa y como funciona, no tienes que pasar toda la informacion ni el codigo, solo explica como funciona todo y donde se ubica cada cosa. En el caso de la documentacion de los promts no vayas a hacer un copiar y pegar, explica como se trabajó (Ya que se desarrolló todo usando ia)

A continuacion te paso la informacion de los contenidos de cada sesion

```