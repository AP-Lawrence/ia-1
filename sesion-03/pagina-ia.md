# Recopilación Integral de Prompts y Requerimientos - Plataforma Web Educativa

Este archivo contiene el historial completo de solicitudes, definiciones técnicas, paletas de colores y prompts generados durante el diseño y conceptualización de la plataforma web de cursos de programación, foro estilo Reddit, retos tipo Codewars y mentorías privadas.

---

## Repositorio del proyecto

🔗 **GitHub:** [DevForge](https://github.com/AP-Lawrence/devforge)


---
## 1. Solicitud Conceptual Inicial
* **Usuario:** 
> Debemos desarrollar un aplicativo web tipo de educacion orientada en cursos de programacion, foros para hablar tipo "reddit", chats privados entre entrenadores y aprendices
> necesito varias ideas de: 
> 1. Como podria ser
> 2. Que cosas podria tener
> 3. Que publico aparte de desarrolladores podria estar interesado
> hazme las preguntas que necesites para tener más contexto

---

## 2. Contexto, Público y Modelo de Negocio
* **Usuario:**
> 1. ¿Cuál es el nivel técnico del público al que apuntan inicialmente? : principiantes
> 2. Cómo imaginas la relación con los entrenadores? 
>   1. Secciones pagas, comprar videos, o clases personalizadas con los entrenadores
> 3. Cuál es el modelo de monetización pensado? Pago por curso individual, cuando el estudiante pague por cada curso a nosotros nos retorne el 10% de cada curso
> Nos gustaria integrar tambien una parte tipo codewars

---

## 3. Primer Prompt Maestro para Maquetación (Stitch)
* **Usuario:**
> Dame un ultimo promp, donde incluyas todos los aspectos tecnicos, visuales, y de funcionalidad de la aplicacion 
> se va a hacer una maquetacion con stitch para publicarse con vercel 
> Dame un promp que se pueda dar a esta IA, con todas su estructuras y ejemplos

---

## 4. Selección de Paleta de Colores
* **Usuario:**
> dame una paleta de colores para la aplicacion con max 5

*(Definición basada en: Slate Dark `#0F172A`, Indigo Vívido `#6366F1`, Esmeralda Código `#10B981`, Rosa Alerta `#F43F5E` y Blanco Nieve `#F8FAFC`).*

---

## 5. Requisitos Funcionales y No Funcionales (Prompt para Stitch / Lógica)
* **Usuario:**
> manda los requisitos funcionales y no funcionales de la pagina, tecnicos y agregalos a un prompt para poder que stich agrege las funcionalidades ya que tenemos ya todo lo visual de la pagina. sea muy especifico con todo

---

## 6. Prompt Final para v0.dev (Integrando Archivos de Stitch)
* **Usuario:**
> Una vez exportado el archivo de stich en formato zip tengo el html, md y una captura. Necesito que siguiendo el flujo de trabajo que llevamos me generes un promt para V0 vercel con el fin de que V0 me genere las funcionalidades completas, le voy a pasar el promt y los archivos del zip
> *(Temperatura configurada entre 0.3 y 0.5)*

## 7. Prompt de Implementación Avanzada de Funcionalidades en DevForge (V0)

Se proporcionó a V0 un prompt maestro para transformar la maquetación inicial de DevForge en una aplicación funcional, utilizando **Next.js**, **App Router**, **TypeScript** y **Tailwind CSS**.

> **Objetivo:** Convertir DevForge en una plataforma SaaS/LMS interactiva, con funcionalidades completas, persistencia de datos, aislamiento multiusuario y una experiencia visual profesional.

### 7.1. Sistema de diseño y refinamiento visual
* Implementación estricta de la paleta oficial de DevForge.
* Tipografías `Space Grotesk`, `Geist` y `JetBrains Mono`.
* Sistema de notificaciones Toast.
* Buscador global mediante Command Palette (`Ctrl + K`).
* Refinamiento de tarjetas, bordes, sombras, animaciones y estados interactivos.

### 7.2. Autenticación y base de datos local
* Implementación de `DevForgeDB` utilizando `localStorage`.
* Simulación de estructura relacional con las tablas:
  * `users`
  * `user_progress`
  * `courses`
  * `course_doubts`
  * `forum_threads`
  * `forum_comments`
  * `direct_messages`
  * `notifications`
* Bloqueo de acceso a la plataforma sin autenticación.
* Separación de información y progreso por usuario.
* Registro de nuevos usuarios con estadísticas iniciales en cero.
* Conservación de los datos semilla del usuario `alex@devforge.dev`.

### 7.3. Evaluación técnica de tutores
Implementación de un examen dinámico para los usuarios que quieran registrarse como tutores.

**La dificultad depende de la tarifa por hora seleccionada:**
* **Nivel 1:** $10-$30 USD/hora. Evaluación Junior-Mid.
* **Nivel 2:** $31-$60 USD/hora. Evaluación Senior.
* **Nivel 3:** $61+ USD/hora. Evaluación Staff/Principal.

**Al aprobar:**
* Se asigna la insignia **Tutor Verificado**.
* Se habilita su publicación en el directorio de mentores.

### 7.4. Panel exclusivo para tutores
* Dashboard personalizado según el rol.
* Administración y edición de cursos.
* Creación de módulos y subtemas.
* Incorporación de contenido Markdown y fragmentos de código.
* Visualización del progreso de los estudiantes.
* Bandeja de dudas de aprendices.
* Sistema de respuestas a consultas.

### 7.5. Reproductor LMS interactivo
Implementación de un reproductor de cursos con:
* **Tres cursos iniciales:**
  1. Fundamentos de JavaScript & DOM.
  2. React: interfaces que escalan.
  3. TypeScript para equipos reales.
* Tres módulos por curso.
* Tres subtemas por módulo.
* Material teórico y ejemplos de código.
* Retos prácticos por lección.
* Validación de ejercicios.
* Sistema de XP (`+25 XP` por lección completada).
* Actualización automática del progreso.

### 7.6. Módulo de retos tipo Codewars
* Catálogo de retos para JavaScript, TypeScript, Python y SQL.
* Clasificación de dificultad desde `8 kyu` hasta `4 kyu`.
* Casos de prueba.
* Validación de soluciones.
* Consola de resultados.
* Registro de tiempos de ejecución.
* Sistema de recompensas XP.
* Desbloqueo de soluciones de la comunidad.

> **Consideración técnica:** La ejecución de JavaScript/TypeScript mediante `new Function` debe tratarse como una solución de demostración, no como un entorno seguro de ejecución de código de usuarios. Para producción se requiere un runner aislado.

### 7.7. Comunidad y foro avanzado
* Publicaciones y comentarios.
* Sistema de upvotes y downvotes.
* Karma de usuarios.
* Soluciones aceptadas.
* Estados de hilos resueltos y sin resolver.
* Filtros por tendencias, recientes, resueltos y guardados.
* Eliminación de comentarios y publicaciones propias.
* Actualización dinámica de contadores.

### 7.8. Notificaciones y personalización
* Campana de notificaciones.
* Registro de mensajes, reservas y respuestas de tutores.
* Notificaciones leídas y no leídas.
* Modo oscuro y modo claro.
* Preferencias visuales individuales por usuario.

### 7.9. Footer y documentación
Implementación de un centro de documentación con:
* Documentación oficial.
* Guía de Karma y rangos Kyu.
* Código de conducta.
* Programa de mentores.
* Estado de la plataforma.

---

## 8. Prompt de Implementación del Sistema de Mensajería y Nuevas Conversaciones

Posteriormente, se proporcionó un prompt adicional a V0 para ampliar el módulo de Mensajes / Chat.

> **Objetivo:** Permitir que cualquier usuario autenticado, independientemente de su rol (Aprendiz o Tutor), pueda iniciar conversaciones privadas con otros usuarios registrados en `DevForgeDB`.

### 8.1. Botón para iniciar conversaciones
* Incorporar el botón **"+ Nuevo Mensaje"** en la bandeja de mensajes.
* Mostrar un modal para iniciar una nueva conversación.
* Mantener la coherencia visual con el sistema de diseño de DevForge.

### 8.2. Buscador de usuarios
Dentro del modal:
* Input de búsqueda en tiempo real.
* Búsqueda por nombre y correo electrónico.
* Listado de usuarios registrados en `DevForgeDB`.
* Exclusión del usuario actualmente autenticado.
* Identificación visual mediante avatares e iniciales.
* Badges para diferenciar Aprendices y Tutores.

### 8.3. Creación y recuperación de conversaciones
Al seleccionar un usuario:
1. Verificar si ya existe una conversación entre ambos.
2. Si existe, abrir el chat correspondiente.
3. Si no existe, crear una nueva conversación.
4. Actualizar el estado global.
5. Abrir el panel de mensajería con el usuario seleccionado.

### 8.4. Experiencia visual
* Modal con bordes redondeados.
* Fondo oscuro.
* Bordes sutiles.
* Botones con acento Indigo.
* Cierre automático después de seleccionar un usuario.
* Toast de confirmación: `"Conversación iniciada con [Nombre del usuario]"`.

> **Resultado esperado:** Un sistema de mensajería privada que permita descubrir usuarios e iniciar conversaciones sin depender de que exista previamente un chat.

---

## 9. Prompt de Migración de Infraestructura: Cloud Database y Sincronización en Tiempo Real

Se proporcionó un último prompt a V0 con el objetivo de evolucionar la arquitectura de DevForge. Hasta este punto, la persistencia estaba basada principalmente en `localStorage`, lo que limitaba la disponibilidad de información entre diferentes navegadores y dispositivos.

> **Objetivo:** Migrar DevForge hacia una arquitectura centralizada en la nube, con autenticación persistente y sincronización de información en tiempo real.

### 9.1. Migración de DevForgeDB a Cloud Database
Se solicitó migrar las siguientes tablas:
* `users`
* `user_progress`
* `courses`
* `course_doubts`
* `forum_threads`
* `forum_comments`
* `direct_messages`
* `notifications`

**Proveedores propuestos:**
* Supabase PostgreSQL.
* Firebase Firestore.

La nueva arquitectura debe permitir que todos los usuarios consulten y actualicen la misma información desde cualquier dispositivo.

### 9.2. Comunidad en tiempo real
Implementación de suscripciones a cambios en la base de datos.

**Eventos que deben sincronizarse:**
* Creación de publicaciones.
* Nuevos comentarios.
* Eliminación de respuestas.
* Votaciones positivas y negativas.

Los cambios deben reflejarse automáticamente en todos los dispositivos conectados, sin necesidad de recargar la página.

### 9.3. Mensajería en tiempo real
* Sincronización de conversaciones entre usuarios.
* Almacenamiento remoto de mensajes.
* Actualización inmediata de chats.
* Notificaciones en tiempo real.
* Actualización del contador de mensajes no leídos.

### 9.4. Autenticación centralizada
Implementación de un proveedor de autenticación con soporte para:
* Tokens JWT.
* Sesiones persistentes.
* Inicio de sesión desde diferentes dispositivos.
* Recuperación del perfil del usuario.
* Recuperación de roles.
* Recuperación de XP y progreso.
* Control de permisos.

### 9.5. Indicador de conexión
Se solicitó incorporar un indicador visual del estado de conexión:
*  **Sincronizado en tiempo real (Cloud).**
*  **Desconectado.**

También se solicitó mostrar notificaciones cuando otros usuarios publiquen contenido en la comunidad.

### 9.6. Estado de implementación

>  **IMPORTANTE: IMPLEMENTACIÓN PENDIENTE DE FINALIZACIÓN.**
> El último prompt no pudo ejecutarse completamente debido a una limitación de tokens de V0. Por tanto, no se debe considerar terminada la migración a Cloud Database ni asumir que existe sincronización real entre dispositivos.

**Es necesario continuar el desarrollo verificando:**
* [ ] Configuración del proveedor de base de datos.
* [ ] Creación y migración del esquema.
* [ ] Configuración de autenticación.
* [ ] Políticas de seguridad y permisos.
* [ ] Sincronización en tiempo real.
* [ ] Migración de los datos existentes.
* [ ] Pruebas multiusuario y multidispositivo.


