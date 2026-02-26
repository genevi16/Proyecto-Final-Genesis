PROYECTO FINAL – TESTING FUNCIONAL Y DE APIs
PLATAFORMA Instagram Lite

------------------------------------------------------------

INTEGRANTE
Génesis Virginia Guatache Colmenares

------------------------------------------------------------

OBJETIVO DEL TESTING

El objetivo del proyecto fue aplicar conocimientos de testing funcional manual sobre la plataforma Instagram Lite

Se buscó validar el correcto funcionamiento de las funcionalidades principales del sistema, el cumplimiento de los criterios de aceptación definidos en las historias de usuario, la correcta validación de datos, el manejo de errores y el comportamiento general del sistema en distintos escenarios positivos y negativos.

------------------------------------------------------------

ALCANCE Y ENTORNO DE PRUEBA

Alcance

El testing incluyó las siguientes épicas:

1. Gestión de Perfil y Acceso
   - Registro de usuario
   - Inicio de sesión
   - Edición de perfil

2. Gestión de Publicaciones
   - Crear publicación
   - Editar publicación
   - Eliminar publicación

3. Gestión de Interacciones
   - Dar "Me gusta"
   - Comentar publicaciones

Se diseñaron 32 casos de prueba funcionales cubriendo flujos principales, validaciones de campos obligatorios, reglas de negocio y control de acceso.

No se incluyeron pruebas de rendimiento ni automatización, ya que el enfoque fue testing funcional manual y validación de APIs.

Entorno de prueba

- Testing manual
- Control de versiones con Git
- Repositorio gestionado en GitHub
- Dispositivo móvil personal
- Sistema operativo Android
- Aplicación Postman para ejecución de pruebas API
- Conexión a internet doméstica (WiFi)
- Repositorio GitHub para gestión de evidencias y documentación
- Pruebas realizadas de forma manual

------------------------------------------------------------

RESULTADOS GENERALES

Se diseñaron 32 casos de prueba.

De los casos ejecutados:
- 29 resultaron OK
- 3 resultaron FAIL

Los defectos encontrados fueron clasificados con severidad media y baja. Ninguno de ellos afecta el flujo principal de las funcionalidades críticas del sistema, como registro, login o creación de publicaciones.

------------------------------------------------------------

CONCLUSIÓN GENERAL

La aplicación cumple correctamente con los flujos principales definidos en las historias de usuario.

Si bien se identificaron 3 defectos, estos no impactan el funcionamiento central del sistema ni impiden la ejecución de las funcionalidades críticas.

Desde el punto de vista funcional, el producto podría ser liberado a producción en su estado actual.

Sin embargo, para garantizar un mayor nivel de calidad y mejorar la experiencia del usuario, se recomienda corregir los defectos identificados y volver a ejecutar las pruebas correspondientes.
