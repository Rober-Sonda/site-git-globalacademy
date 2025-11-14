Propital

Bienvenidos al repositorio de la comisión 21
Instructivo para descargar el repositorio
Antes de comenzar asegurate tener instalado GIT en la computadora. Para revisar escribe en el buscador de Windows o del sistema operativo que tengas el programa GIT BASH. Si lo tienes está instalado correctamente.

Escribir en el buscador de windows el siguiente comando y luego dar Enter.
  cmd
Hacer click en el boton verde que dice "Code" del repositorio y copiar el enlace que allí figura.

Ir a la terminal que abrieron con el cmd y escribir el siguiente comando. Nota: Revisen bien en que carpeta van a ejecutar el comando para luego poder encontrar el archivo que se genera.

  git clone pegar_enlace_extraido_del_boton_Code
Una vez que ejecutan ese comando se debería crear una carpeta en la ubicación que figura en la terminal. Una vez que la carpeta se genera ya pueden arrastrarla al ícono de Visual Studio Code.
Comandos para recorrer en terminal
Moverte a un archivo/carpeta (directorio) interno de la carpeta actual (directorio actual).
  cd nombre_archivo
Regresar al directorio anterior.
  cd ..
Revisar todos los archivos del directorio actual
  dir
Crear una nueva carpeta
  mkdir nombre_carpeta
Limpiar terminal
  cls
Cerrar terminal
  exit
COMANDOS GIT
git init: inicializa git en un proyecto.
git remote add origin [enlace repo]: Conecta un proyecto con un repositorio.
git remote set-url origin [enlace nuevo repo]: Desvincula el proyecto de un repo, y lo vinculo al nuevo.
Preparamos nuestros cambios para ser enviados al repositrio.
git add [nombre achivo]: Registra un archivo para ser enviado al repo.
git add . : Registra todos los archivos.
Preparamos el backup
git commit -m [nombre commit]: Prepara una version segura a la cual podemos volver (un backup).
Enviamos las actualizaciones al repo
git push: Envia las actualizaciones a una rama generica
git push origin [nombre rama]: Envia las actualizacions a una rama origen (default)
Para revisar informacion
git status: Revisamos que esta registrado y que no. (rojo: no registrado. Verde: Registrado)
git log: revisamos la lista de commits realizados. (El que tiene el HEAD es el ultimo y apunta a la rama en la cual se realizó.)
Descargar de repo a PC
git clone [enlace repo]: Clona el proyecto del repo a la PC
Cambiar de rama
git checkout [nombre rama]
Actualizar el proyecto de repo a PC
git pull: Arrastra cambios que existen en el repo pero no en la PC, del repo a la PC.
Establecer tus datos de username e email
git config --global user.email "aldanacapoble@gmail.com"
git config --global user.name "Aldana Capoble"
Dar colaborador
Entran al repo -> Settings -> Collaborators -> Add people -> Buscan a "lirico" (Matias Dominguez) avatar de atomo.

====================================================
Aprende Git - Guía Completa de Control de Versiones
====================================================

Descripción General
-------------------

Este proyecto constituye un sitio web educativo integral dedicado a la enseñanza de Git desde sus fundamentos hasta técnicas avanzadas. Diseñado específicamente para desarrolladores hispanohablantes que desean dominar el control de versiones, la guía presenta los conceptos de manera progresiva, clara y con un enfoque pedagógico profesional.

La arquitectura del sitio está construida exclusivamente con HTML5 semántico puro, sin dependencias de CSS o JavaScript, priorizando la accesibilidad universal, la claridad del contenido y la compatibilidad con cualquier navegador o dispositivo.


Objetivos del Proyecto
-----------------------

- Proporcionar una educación completa sobre Git adaptada al público hispanohablante
- Explicar no solo el "cómo" sino también el "por qué" detrás de cada concepto y comando
- Facilitar el aprendizaje mediante analogías comprensibles y ejemplos prácticos reales
- Preparar a los desarrolladores para trabajar profesionalmente en equipos de software
- Ofrecer una referencia rápida y consulta permanente para usuarios de todos los niveles


Estructura del Contenido
-------------------------

El sitio está organizado en ocho módulos temáticos independientes pero secuenciales:

- Introducción al Control de Versiones
  Explica qué son los sistemas de control de versiones, su historia, problemas que resuelven y por qué Git se convirtió en el estándar industrial. Incluye comparaciones con sistemas anteriores y casos de uso reales.

- Qué es Git y el Modelo Distribuido
  Profundiza en la arquitectura distribuida de Git, cómo funciona internamente, qué lo diferencia de sistemas centralizados y por qué es revolucionario. Contiene diagramas conceptuales y analogías visuales.

- Instalación y Configuración
  Guía detallada paso a paso para instalar Git en Windows, macOS y Linux. Cubre configuraciones iniciales obligatorias, configuración de identidad, alias útiles, editores de texto y preparación del entorno de desarrollo.

- Comandos Esenciales
  Exposición completa de los comandos fundamentales: add, commit, status, log, diff, restore, reset y más. Explica los tres estados de Git (Working Directory, Staging Area, Repository) con ejemplos prácticos detallados.

- Ramas y Branching
  Análisis profundo de la característica más poderosa de Git: el sistema de ramas. Enseña a crear, fusionar, eliminar y gestionar ramas, resolver conflictos de fusión, diferencias entre merge y rebase, y estrategias de branching profesionales como Git Flow.

- Flujo Completo: Trabajo Local y Remoto
  Conecta el trabajo local con repositorios remotos en plataformas como GitHub y GitLab. Dominio de push, pull, fetch, clone, fork y colaboración mediante Pull Requests. Incluye autenticación SSH, tokens de acceso y flujos de trabajo colaborativos.

- Práctica y Casos Reales
  Ejercicios guiados paso a paso: creación del primer proyecto, simulación de trabajo en equipo, resolución práctica de conflictos, contribución a proyectos open source. Incluye casos reales como recuperación de archivos borrados y corrección de commits erróneos.

- Recursos Adicionales y Mejores Prácticas
  Errores comunes y sus soluciones, mejores prácticas profesionales, herramientas complementarias (GUI clients, extensiones de VS Code), Git Hooks, cheat sheet completo de comandos, y recursos de aprendizaje continuo recomendados.


Características Técnicas
-------------------------

- HTML5 semántico puro sin CSS ni JavaScript
- Enfoque en accesibilidad universal y compatibilidad multiplataforma
- Navegación mediante enlaces internos y externos claramente estructurados
- Sistema de navegación bidireccional entre páginas (anterior/siguiente)
- Enlaces de retorno al inicio en cada sección para facilitar la navegación
- Estructura modular que permite consulta no lineal del contenido
- Formato responsive nativo mediante HTML semántico
- Contenido completamente en español con terminología técnica apropiada
- Ejemplos de código formateados con la etiqueta pre para mantener formato
- Tablas de referencia para consulta rápida de comandos


Arquitectura de Archivos
-------------------------

La estructura del proyecto está organizada de la siguiente manera:

index.html                      Página principal y hub de navegación central
pages/
  - git-introduccion.html       Introducción al control de versiones
  - git-que-es.html             Arquitectura y modelo distribuido de Git
  - git-instalacion.html        Instalación y configuración del entorno
  - git-comandos.html           Comandos esenciales y flujo básico
  - git-ramas.html              Sistema de ramas y branching avanzado
  - git-flujo.html              Integración local-remoto y colaboración
  - git-practica.html           Ejercicios prácticos y casos reales
  - git-recursos.html           Recursos adicionales y mejores prácticas
lang/
  - en.json                     Archivo de idioma inglés (futuro uso)
  - es.json                     Archivo de idioma español (futuro uso)
README.md                       Documentación del proyecto


Metodología Pedagógica
-----------------------

El contenido educativo está diseñado con múltiples técnicas de enseñanza complementarias:

- Explicaciones tipo profesor universitario
  Cada concepto se explica con profundidad académica pero lenguaje accesible, asumiendo cero conocimiento previo pero respetando la inteligencia del lector.

- Analogías del mundo real
  Los conceptos abstractos de Git se comparan con situaciones cotidianas comprensibles: control de versiones como "puntos de guardado en videojuegos", ramas como "universos paralelos", etc.

- Ejemplos de código reales
  Todos los comandos incluyen ejemplos ejecutables reales con explicaciones línea por línea de qué hace cada parámetro.

- Casos de uso profesionales
  Se presentan escenarios reales del mundo laboral: trabajo en equipo, resolución de conflictos, despliegue a producción, contribución a proyectos open source.

- Progresión incremental
  El contenido avanza de lo simple a lo complejo, asegurando que cada nuevo concepto se construya sobre conocimientos previamente establecidos.

- Ejercicios prácticos guiados
  Instrucciones paso a paso para ejecutar comandos reales y ver sus resultados, permitiendo aprendizaje activo mediante experimentación.


Público Objetivo
----------------

Este material está diseñado específicamente para:

- Desarrolladores principiantes sin experiencia previa en control de versiones
- Estudiantes de informática y programación que necesitan aprender Git
- Profesionales que usan Git básicamente y desean profundizar su conocimiento
- Equipos de desarrollo que requieren una referencia común en español
- Autodidactas que prefieren aprender mediante documentación estructurada
- Instructores y profesores que buscan material educativo completo en español


Modo de Uso
------------

Para utilizar esta guía:

- Para navegación web local: Abrir el archivo index.html en cualquier navegador moderno
- Para lectura secuencial completa: Seguir el orden de los módulos desde Introducción hasta Recursos
- Para consulta rápida: Usar el índice de la página principal para saltar directamente al tema deseado
- Para aprendizaje activo: Tener una terminal abierta y ejecutar cada comando mientras se lee
- Para referencia permanente: Guardar el sitio localmente o marcarlo para consulta futura


Requisitos Técnicos
--------------------

- Navegador web moderno con soporte HTML5 (Chrome, Firefox, Safari, Edge, Opera)
- No se requiere conexión a internet después de descargar los archivos
- No se necesitan dependencias externas, frameworks o bibliotecas
- Compatible con lectores de pantalla y tecnologías de accesibilidad
- Funciona en cualquier sistema operativo: Windows, macOS, Linux, móviles


Filosofía del Proyecto
-----------------------

Este proyecto se fundamenta en varios principios rectores:

- Accesibilidad universal sobre estética visual
- Contenido educativo profundo sobre simplicidad superficial
- Español como idioma principal para reducir barreras de aprendizaje
- HTML semántico puro para máxima compatibilidad y rendimiento
- Explicaciones completas que respeten la inteligencia del lector
- Enfoque en comprensión conceptual además de conocimiento procedimental
- Material gratuito y abierto para democratizar la educación en tecnología


Casos de Uso del Material
--------------------------

Este recurso educativo puede emplearse en diversos contextos:

- Autoaprendizaje individual a ritmo propio
- Material de apoyo en cursos universitarios de ingeniería de software
- Documentación de referencia en empresas de desarrollo
- Recurso de onboarding para nuevos desarrolladores en equipos
- Material de estudio para preparación de entrevistas técnicas
- Base para talleres y capacitaciones corporativas sobre Git
- Referencia rápida durante el trabajo diario con Git


Próximas Mejoras Planificadas
------------------------------

Aunque el proyecto está completo y funcional, se contemplan mejoras futuras:

- Implementación del sistema de internacionalización usando los archivos JSON en lang/
- Versión para impresión en PDF con formato optimizado
- Ejercicios interactivos opcionales mediante JavaScript progresivo
- Sección de preguntas frecuentes expandida basada en feedback de usuarios
- Ejemplos adicionales de flujos de trabajo empresariales complejos
- Integración con herramientas de CI/CD y automatización


Contribuciones y Feedback
--------------------------

Este es un proyecto educativo en evolución. Se agradece feedback sobre:

- Errores técnicos o imprecisiones en el contenido
- Sugerencias de temas adicionales a cubrir
- Mejoras en las explicaciones o analogías existentes
- Casos de uso reales que deberían incluirse
- Problemas de accesibilidad o compatibilidad detectados


Información de Autoría
-----------------------

Creado por: Rober Sonda
Año de publicación: 2025
Propósito: Material educativo gratuito para la comunidad de desarrollo de software
Idioma principal: Español
Tecnologías utilizadas: HTML5 semántico puro


Licencia y Uso
--------------

Este proyecto es material educativo de uso libre para fines académicos y de aprendizaje. Se permite:

- Uso personal para aprendizaje individual
- Uso en instituciones educativas como material de curso
- Distribución libre manteniendo atribución al autor
- Modificación y adaptación para contextos educativos específicos
- Traducción a otros idiomas manteniendo créditos originales

No se permite uso comercial directo sin autorización explícita del autor.


Agradecimientos
---------------

Este proyecto se construyó sobre el conocimiento colectivo de la comunidad de desarrollo de software, las guías oficiales de Git, y años de experiencia práctica en equipos de desarrollo profesionales. Se agradece especialmente a la comunidad hispanohablante de desarrolladores por la necesidad identificada de material educativo de calidad en español.


Contacto y Soporte
------------------

Para consultas, sugerencias o reporte de problemas relacionados con el contenido educativo de esta guía, se puede contactar mediante los canales especificados en la sección de contacto del sitio web.


Última Actualización
---------------------

Versión actual: 1.0
Fecha de última revisión: Noviembre 2025
Estado del proyecto: Completo y en mantenimiento activo
