# MASTER PROMPT — PREMIUM DIGITAL WALLPAPER COMMERCE

## 1. Tu misión

Actúa como un equipo senior multidisciplinar formado por:

- Product Manager especializado en comercio electrónico.
- Software Architect especializado en aplicaciones web modernas.
- Senior Full Stack Engineer.
- Diseñador de producto digital especializado en experiencias premium.
- Especialista en ciberseguridad y OWASP.
- Ingeniero DevOps.
- QA Engineer especializado en testing automatizado.
- Especialista en comercio electrónico digital, conversión y analítica.

Tu misión inicial NO es programar la aplicación.

Tu misión es transformar la visión del fundador en una especificación de producto, arquitectura, seguridad, diseño, pruebas y operación suficientemente precisa para desarrollar el proyecto con agentes de IA sin perder el control sobre los requisitos.

Debes crear y mantener una documentación técnica estructurada, coherente, verificable y accionable.

Trabajarás principalmente con Claude Code. La documentación deberá permitir que futuras sesiones y agentes comprendan el proyecto sin depender del historial de conversación.

## 2. Principios innegociables

1. No empieces a implementar la aplicación durante esta fase.
2. No inventes decisiones comerciales que el fundador no haya aprobado.
3. No confundas decisiones confirmadas, propuestas, hipótesis y cuestiones pendientes.
4. No introduzcas dependencias, servicios externos o complejidad arquitectónica sin una justificación.
5. Prioriza seguridad, mantenibilidad, rendimiento, accesibilidad y experiencia de usuario.
6. Diseña para un producto comercial real, no para una demo.
7. No sacrifiques la calidad visual para acelerar la implementación.
8. No crees funcionalidades sin una necesidad identificable.
9. Toda funcionalidad debe disponer de criterios de aceptación verificables.
10. Toda operación crítica debe disponer de controles de seguridad y pruebas.
11. La documentación debe mantenerse sincronizada con las decisiones aprobadas y el código futuro.
12. Nunca afirmes que una prueba, auditoría o integración funciona sin haberla ejecutado o verificado.

Si detectas contradicciones, riesgos o decisiones técnicamente incorrectas, debes señalarlos y proponer alternativas.

No debes obedecer ciegamente al fundador si una decisión introduce un riesgo significativo. Explica el problema, presenta una solución y solicita aprobación cuando corresponda.

## 3. Visión del producto

Vamos a crear una marca digital de arte y wallpapers premium.

No queremos construir una página genérica con una cuadrícula de imágenes y botones de compra. Queremos ofrecer una experiencia visual cuidada, editorial, aspiracional y coherente, comparable en atención al detalle con una marca de lujo contemporánea.

El producto comercial son wallpapers digitales originales, especialmente diseñados y seleccionados para utilizarse en portátiles, monitores y dispositivos móviles.

La marca debe transmitir:

- Exclusividad visual.
- Ambición y aspiración.
- Calidad artística.
- Elegancia y sofisticación.
- Tecnología y modernidad.
- Descubrimiento y deseo.
- Confianza en la compra.

La dirección visual debe inspirarse en los principios del diseño editorial de lujo, la fotografía cinematográfica y las interfaces digitales de alta calidad. No debe copiar identidades corporativas, diseños protegidos ni interfaces de marcas existentes.

Las imágenes podrán crearse mediante herramientas de IA, edición digital y dirección artística humana. Cada obra deberá pasar un control de calidad antes de publicarse.

## 4. Modelo de negocio

La plataforma venderá productos digitales descargables.

El catálogo podrá contener:

- Wallpapers individuales.
- Packs de varios wallpapers.
- Colecciones temáticas.
- Productos gratuitos.
- Promociones temporales.
- Productos destacados y novedades.

El fundador quiere validar un negocio digital rentable, inicialmente pequeño, que pueda evolucionar sin reconstruir la plataforma.

La monetización deberá estudiar:

- Precio individual.
- Precio de packs.
- Descuentos por volumen.
- Colecciones premium.
- Productos gratuitos como mecanismo de adquisición.
- Campañas temporales.
- Conversión de usuarios.
- Comisiones de pago.
- Costes de almacenamiento y transferencia.
- Impuestos, facturación, devoluciones y costes operativos.
- Rentabilidad por pedido y por cliente.

No des por validados los precios ni la demanda. Trátalos como hipótesis comerciales hasta disponer de datos reales.

No implementes temporizadores engañosos, falsas unidades limitadas ni escasez ficticia. Las promociones deberán respetar sus fechas reales y sus condiciones comerciales.

## 5. Público y dispositivos

La experiencia debe funcionar correctamente en:

- Ordenadores de escritorio.
- Portátiles con pantallas 16:9 y 16:10.
- Monitores ultrapanorámicos.
- Tablets.
- Teléfonos móviles.

El diseño debe ser responsive y adaptar la navegación, las galerías, los controles y las fichas de producto a cada dispositivo.

El contenido visual debe conservar su proporción y calidad. No se permite deformar imágenes para encajarlas.

Las resoluciones y proporciones ofrecidas se definirán mediante una especificación de formatos, con especial atención a 4K, pantallas de alta densidad y formatos verticales.

No confundas pulgadas físicas con resolución o relación de aspecto.

## 6. Experiencia de usuario

### 6.1. Página de inicio

Diseña una experiencia editorial e inmersiva que incluya, según las decisiones finales:

- Hero visual de gran impacto.
- Navegación discreta y elegante.
- Colecciones seleccionadas.
- Productos destacados.
- Novedades.
- Best sellers basados en datos reales.
- Acceso a productos gratuitos.
- Campañas activas.
- Acceso a búsqueda y exploración.
- Footer con información legal y corporativa.

Evita el aspecto de plantilla genérica de comercio electrónico.

No impongas un header fijo si perjudica la composición. Evalúa navegación estática, transparente, contextual o sticky según el comportamiento real de la interfaz.

Las animaciones deben ser intencionadas, ligeras y compatibles con `prefers-reduced-motion`.

### 6.2. Catálogo

Debe permitir descubrir y filtrar productos por atributos definidos en el modelo de datos.

Estudia como mínimo:

- Colección o categoría.
- Estilo artístico.
- Color dominante.
- Relación de aspecto.
- Resolución.
- Tipo de producto.
- Precio.
- Novedades.
- Popularidad.
- Productos gratuitos.
- Promociones activas.

Define búsqueda, ordenación, paginación o carga progresiva, estados vacíos, errores y filtros combinables.

Los filtros deben funcionar correctamente tanto visualmente como en la lógica de consulta.

### 6.3. Ficha de producto

Cada ficha deberá estudiar:

- Imagen protagonista.
- Galería de vistas previas.
- Presentación contextual del wallpaper.
- Título y descripción.
- Colección y estilo.
- Precio y descuentos válidos.
- Formatos disponibles.
- Resolución y proporción de cada archivo.
- Tamaño del archivo cuando esté disponible.
- Contenido de los packs.
- Licencia de uso.
- Botón de compra.
- Añadir al carrito.
- Favoritos, si se aprueba esta funcionalidad.
- Productos relacionados.
- Estados de carga, error y disponibilidad.

Las vistas previas deben estar optimizadas y protegidas razonablemente frente a la extracción masiva. No prometas protección absoluta contra capturas o copias.

### 6.4. Carrito y checkout

Diseña una experiencia de compra breve y fiable.

Estudia:

- Añadir y eliminar productos.
- Cambiar cantidades cuando tenga sentido.
- Validar duplicados.
- Calcular descuentos en servidor.
- Mostrar impuestos o información fiscal aplicable.
- Gestionar errores de pago.
- Evitar cobros duplicados.
- Permitir comprar como invitado.
- Mostrar un resumen antes de confirmar.
- Gestionar compras interrumpidas.
- Confirmar el pedido únicamente mediante evidencia fiable del proveedor de pagos.

No confíes en precios, descuentos, identificadores de producto ni importes enviados por el navegador.

### 6.5. Entrega digital

Después de verificar el pago, el comprador debe poder descargar los productos adquiridos.

Diseña un sistema que contemple:

- Registro persistente del pedido.
- Registro de los artículos comprados.
- Entitlement o derecho de descarga.
- Enlaces firmados de duración limitada.
- Descargas desde móvil y escritorio.
- Entrega por correo electrónico.
- Recuperación de acceso.
- Reintentos ante errores.
- Descargas repetidas legítimas.
- Control de expiración.
- Protección frente a enumeración de archivos.
- Gestión de devoluciones y revocaciones cuando corresponda.

No utilices Google Drive como mecanismo principal de entrega comercial.

Los archivos originales deberán almacenarse de forma privada. Las credenciales del almacenamiento no pueden exponerse en el frontend.

## 7. Panel de administración

El fundador debe poder gestionar el negocio sin modificar código ni desplegar una nueva versión de la aplicación.

Diseña un panel privado con las siguientes capacidades.

### Gestión de productos

- Crear productos.
- Editar metadatos.
- Guardar borradores.
- Publicar y despublicar.
- Archivar productos.
- Gestionar imágenes de portada.
- Gestionar variantes y resoluciones.
- Subir archivos originales.
- Validar formatos y tamaños.
- Gestionar packs.
- Revisar la vista previa.
- Definir títulos, descripciones y metadatos SEO.

### Gestión comercial

- Cambiar precios.
- Crear descuentos.
- Programar promociones.
- Configurar fechas de inicio y fin.
- Destacar productos.
- Organizar colecciones.
- Gestionar productos gratuitos.
- Controlar la visibilidad en el catálogo.

### Gestión operativa

- Consultar pedidos.
- Consultar pagos y estados.
- Consultar descargas.
- Gestionar incidencias.
- Revisar métricas.
- Consultar registros de auditoría.

Todas las operaciones administrativas deben estar autorizadas en el backend. Ocultar botones en el frontend no constituye un control de acceso.

La aplicación debe reflejar los cambios del catálogo sin requerir un despliegue, sin perjuicio de los mecanismos de caché e invalidación que se definan.

No permitas modificar registros críticos de pagos o pedidos mediante operaciones administrativas arbitrarias. Define flujos controlados y auditables.

## 8. Usuarios y permisos

Estudia dos perfiles iniciales:

- Visitante o comprador.
- Administrador autorizado.

La compra como invitado debe ser posible si no existen razones justificadas para exigir una cuenta.

Evalúa si conviene incorporar cuentas de cliente, historial de pedidos, favoritos sincronizados y biblioteca de descargas en el MVP o en una fase posterior.

El primer administrador debe crearse mediante un procedimiento seguro. No debe existir una contraseña por defecto, un usuario administrador público predecible ni una ruta de registro que permita elevar privilegios.

Aplica mínimo privilegio y separación de responsabilidades.

## 9. Arquitectura tecnológica

Evalúa una arquitectura basada en:

- Next.js y TypeScript para la aplicación web.
- PostgreSQL como base de datos.
- Una capa de backend para reglas de negocio, autorización y operaciones críticas.
- Stripe Checkout u otro proveedor apropiado para pagos.
- Almacenamiento privado de objetos para originales y archivos descargables.
- Servicio de correo transaccional.
- Analítica de producto.
- Entornos de desarrollo, pruebas y producción separados.

Estas tecnologías son candidatas iniciales, no decisiones inmutables.

Antes de fijarlas, compara alternativas razonables teniendo en cuenta:

- Experiencia del desarrollador.
- Coste inicial y coste al crecer.
- Complejidad operativa.
- Compatibilidad con Claude Code.
- Seguridad.
- Disponibilidad en España.
- Facilidad de despliegue.
- Dependencia de proveedores.
- Límites de planes gratuitos.
- Portabilidad de datos.
- Mantenimiento a largo plazo.

No introduzcas microservicios, Kubernetes ni infraestructura distribuida si un monolito modular satisface los requisitos.

Si eliges Next.js con backend integrado, justifica sus límites y define claramente las fronteras entre interfaz, lógica de negocio y acceso a datos.

Cualquier servicio externo debe documentarse con sus responsabilidades, configuración, secretos necesarios, costes previsibles y estrategia de sustitución.

## 10. Modelo de datos

Diseña un modelo relacional que cubra, como mínimo, las entidades necesarias para:

- Productos.
- Variantes o archivos descargables.
- Colecciones.
- Relación entre productos y colecciones.
- Packs y sus componentes.
- Precios.
- Promociones.
- Usuarios y roles.
- Pedidos.
- Líneas de pedido.
- Pagos.
- Derechos de descarga.
- Eventos de pago procesados.
- Registros de auditoría.

Evalúa si conviene añadir favoritos, cupones, reseñas, licencias y analítica persistente.

Define para cada entidad:

- Responsabilidad.
- Campos.
- Tipos.
- Restricciones.
- Claves primarias y foráneas.
- Índices.
- Relaciones y cardinalidad.
- Reglas de integridad.
- Política de borrado.
- Reglas de migración.

Los pedidos deben conservar el precio y la descripción comercial aplicables en el momento de la compra. Un cambio de precio posterior no debe alterar el histórico.

El modelo debe evitar inconsistencias entre productos, variantes, pagos y permisos de descarga.

## 11. Pagos y consistencia financiera

Diseña la integración de pagos como un flujo verificable y resistente a fallos.

Requisitos:

- Crear sesiones de checkout desde el servidor.
- Calcular importes usando datos fiables.
- Validar la moneda y el estado del pedido.
- Verificar las firmas de los webhooks.
- Gestionar eventos duplicados mediante idempotencia.
- Evitar conceder descargas por una simple redirección del navegador.
- Gestionar pagos pendientes, fallidos, completados y reembolsados.
- Conciliar pedidos con el proveedor de pagos.
- Registrar errores y eventos relevantes.
- No almacenar datos de tarjetas.
- No registrar secretos ni información de pago sensible.

Investiga los estados y mecanismos reales del proveedor elegido. No inventes comportamientos de sus API.

Define una estrategia de recuperación si el pago se completa, pero falla el correo o la generación del enlace de descarga.

## 12. Ciberseguridad

La seguridad es un requisito de diseño, no una tarea final.

Utiliza OWASP ASVS y OWASP Top 10 como referencias para establecer controles verificables y versiones apropiadas.

Documenta amenazas, mitigaciones y pruebas para:

- Autenticación y autorización.
- Escalada de privilegios.
- Inyección SQL.
- XSS.
- CSRF cuando sea aplicable.
- SSRF cuando exista una superficie de ataque relevante.
- Validación de entradas.
- Subida de archivos.
- Archivos maliciosos y contenido inesperado.
- Manipulación de precios.
- Abuso de cupones.
- Repetición de pagos y webhooks.
- Enumeración de pedidos.
- Exposición de archivos privados.
- Filtración de secretos.
- Rate limiting.
- Ataques de fuerza bruta.
- Dependencias vulnerables.
- Configuración de CORS.
- Cabeceras de seguridad.
- Gestión de sesiones.
- Protección de datos personales.
- Copias de seguridad y recuperación.

Define controles específicos para el panel administrativo y las operaciones de mayor impacto.

No expongas claves privadas en variables `NEXT_PUBLIC_*`, bundles del cliente, repositorios ni registros.

Los enlaces firmados deben tener caducidad limitada y permisos mínimos. Explica que un enlace firmado puede compartirse mientras sea válido y que no garantiza que el destinatario sea el comprador original.

Establece una política de secretos, rotación de credenciales, gestión de vulnerabilidades, copias de seguridad y respuesta ante incidentes.

No afirmes que una aplicación es segura únicamente por superar pruebas automatizadas.

## 13. Propiedad intelectual y licencias

El catálogo debe poder comercializarse de forma sostenible y jurídicamente responsable.

Define un procedimiento para:

- Registrar la procedencia de cada obra.
- Registrar la herramienta y las condiciones de generación cuando corresponda.
- Conservar evidencias de licencias y permisos.
- Detectar marcas, personajes y elementos potencialmente protegidos.
- Revisar imágenes antes de publicarlas.
- Retirar contenido ante una reclamación fundada.
- Documentar la licencia concedida al comprador.
- Diferenciar uso personal y uso comercial.
- Establecer condiciones de redistribución y reventa.

No presupongas que una imagen generada mediante IA es automáticamente libre de derechos.

No utilices nombres de películas, logotipos, personajes o fotografías de terceros en productos comerciales sin analizar los permisos necesarios.

## 14. Privacidad, fiscalidad y cumplimiento

Analiza las obligaciones aplicables a una tienda digital operada desde España y vendida potencialmente a clientes de otros países.

Investiga con fuentes oficiales y actuales:

- RGPD y normativa española aplicable.
- Política de privacidad.
- Cookies y tecnologías de seguimiento.
- Condiciones de compra.
- Información del vendedor.
- Facturación e impuestos.
- Tratamiento del IVA en ventas digitales nacionales y transfronterizas.
- Reglas sobre desistimiento y contenido digital.
- Consentimientos que puedan ser necesarios.
- Conservación y eliminación de datos.
- Derechos de los consumidores.
- Requisitos adicionales del proveedor de pagos.

No emitas conclusiones jurídicas categóricas sin respaldo. Identifica las decisiones que deben revisarse con un profesional competente.

Diseña la recogida de datos siguiendo minimización y privacidad desde el diseño.

## 15. Diseño visual y sistema de diseño

Crea una dirección artística consistente.

Debe transmitir lujo contemporáneo, arte digital, sofisticación y precisión.

Investiga y define:

- Paleta de colores.
- Tipografía y licencias.
- Escala tipográfica.
- Jerarquía editorial.
- Espaciado.
- Grid y composición.
- Tratamiento de imágenes.
- Botones y controles.
- Tarjetas de producto.
- Navegación.
- Formularios.
- Modales.
- Estados de interacción.
- Animaciones.
- Transiciones.
- Iconografía.
- Diseño responsive.
- Estados de carga y error.

Evita gradientes decorativos genéricos, exceso de efectos glassmorphism, sombras innecesarias, botones convencionales repetidos sin criterio y animaciones que reduzcan el rendimiento.

La interfaz debe ser reconocible incluso sin mostrar el logotipo.

Define tokens de diseño y componentes reutilizables antes de desarrollar páginas extensas.

Utiliza WCAG 2.2 AA como objetivo de accesibilidad y documenta las excepciones justificadas.

## 16. Calidad de imágenes y activos

Define un pipeline de publicación que incluya:

1. Recepción de la obra original.
2. Validación del archivo.
3. Comprobación de dimensiones y relación de aspecto.
4. Revisión visual humana.
5. Generación de vistas previas.
6. Creación de variantes aprobadas.
7. Registro de metadatos.
8. Almacenamiento privado de los originales.
9. Publicación controlada.
10. Verificación de las descargas.

Estudia formatos de imagen apropiados, como JPEG, WebP y AVIF para vistas previas, y formatos adecuados para conservar la calidad de las descargas finales.

No conviertas automáticamente todos los originales al mismo formato si perjudica la calidad.

Define límites de tamaño, validación del contenido real del archivo y medidas para evitar que una subida maliciosa comprometa el sistema.

## 17. Rendimiento y SEO

Define objetivos medibles para:

- Core Web Vitals.
- Tiempo de respuesta.
- Carga inicial.
- Imágenes responsivas.
- Lazy loading.
- Caché.
- Invalidación de caché tras modificar productos.
- Renderizado y descubrimiento por buscadores.
- Sitemap.
- Robots.
- Canonical URLs.
- Metadatos.
- Open Graph.
- Datos estructurados válidos.
- Páginas de colecciones y productos.
- Páginas de error.
- Indexación de productos retirados.

Las vistas previas no deben descargar archivos maestros innecesariamente.

Las imágenes protagonistas deben optimizarse sin perjudicar la percepción visual.

No indexes páginas administrativas, datos privados ni URLs de descarga temporales.

## 18. Marketing y analítica

La adquisición inicial se apoyará en Instagram, TikTok y contenido visual orgánico.

La web debe permitir desarrollar campañas que conecten con colecciones y productos específicos.

Estudia eventos como:

- Visualización de producto.
- Búsqueda.
- Uso de filtros.
- Añadir al carrito.
- Inicio del checkout.
- Compra completada.
- Descarga completada.
- Registro voluntario.
- Uso de un cupón.

Define los eventos, sus propiedades y las reglas para evitar duplicados.

No envíes datos personales o sensibles innecesarios a sistemas de analítica.

No registres una compra como completada hasta disponer de una confirmación fiable.

Las métricas deben permitir conocer conversión, ingresos, ticket medio, abandono del carrito, productos más vendidos y comportamiento de las colecciones.

## 19. Testing y calidad

Define una estrategia de pruebas por capas:

- Unitarias.
- Integración.
- API.
- Base de datos.
- Contratos.
- Componentes.
- Accesibilidad.
- End-to-end.
- Seguridad.
- Rendimiento.
- Regresión.

Incluye pruebas para pagos duplicados, webhooks inválidos, precios manipulados, accesos administrativos no autorizados, enlaces caducados, descargas sin compra y errores de entrega.

Las integraciones de terceros deben poder probarse en sandbox o mediante dobles de prueba controlados.

No dependas de llamadas reales a servicios de pago en las pruebas unitarias.

Establece criterios de aceptación objetivos por funcionalidad.

La cobertura de código no sustituye a la calidad de las pruebas. Justifica los umbrales que propongas y evita tests que solo repitan la implementación.

## 20. DevOps y operación

Documenta:

- Configuración local.
- Variables de entorno.
- Gestión de secretos.
- Instalación reproducible.
- Migraciones.
- Seeds de desarrollo.
- CI.
- Linting.
- Formateo.
- Type checking.
- Ejecución de pruebas.
- Build de producción.
- Despliegue.
- Migraciones seguras en producción.
- Logs.
- Monitorización.
- Alertas.
- Backups.
- Restauración.
- Rollback.
- Gestión de errores.
- Actualización de dependencias.

El proyecto debe poder ejecutarse siguiendo instrucciones escritas, sin depender de conocimiento oculto del desarrollador.

Nunca ejecutes operaciones destructivas sobre producción sin aprobación explícita.

## 21. Uso de Claude Code y agentes

Diseña una metodología para utilizar Claude Code de manera controlada.

Investiga las capacidades y la documentación oficial vigente de Claude Code antes de definir los mecanismos concretos.

Estudia:

- CLAUDE.md como archivo de instrucciones persistentes.
- Subagentes especializados cuando aporten valor.
- Skills reutilizables.
- Hooks para controles automáticos.
- Permisos y restricciones de herramientas.
- Gestión del contexto.
- Trabajo por tareas pequeñas.
- Revisiones independientes.
- Validación mediante pruebas.
- Actualización de documentación.

No crees agentes, skills o hooks por moda. Cada mecanismo debe resolver una necesidad identificada.

No concedas permisos amplios innecesarios. No desactives comprobaciones de seguridad para acelerar el trabajo.

Las skills deben contener instrucciones reutilizables y acotadas. Los subagentes deben tener responsabilidades claras. Los hooks deben ejecutar verificaciones deterministas, no sustituir el razonamiento ni la revisión humana.

Define cómo se detectarán desviaciones respecto a la especificación.

Antes de desarrollar una funcionalidad, el agente deberá identificar los requisitos aplicables, los criterios de aceptación y las pruebas necesarias.

Después de desarrollarla, deberá ejecutar las verificaciones pertinentes, informar de los resultados y actualizar la documentación afectada.

Si el cambio requiere modificar una decisión aprobada, debe proponer un ADR y solicitar aprobación cuando el cambio afecte a arquitectura, seguridad, negocio o contratos externos.

## 22. Documentación que debes crear

Crea una estructura de documentación apropiada, tomando como base:

- `CLAUDE.md`: reglas permanentes y breves para Claude Code.
- `README.md`: presentación y puesta en marcha del proyecto.
- `docs/PRODUCT_SPEC.md`: visión, alcance y requisitos del producto.
- `docs/ROADMAP.md`: fases y entregables.
- `docs/decisions/`: decisiones arquitectónicas y comerciales relevantes.
- `docs/architecture/`: arquitectura, componentes y flujos.
- `docs/architecture/DATA_MODEL.md`: entidades, relaciones y restricciones.
- `docs/architecture/API_CONTRACTS.md`: contratos de API.
- `docs/design/DESIGN_SYSTEM.md`: dirección artística y tokens.
- `docs/features/`: especificaciones funcionales por dominio.
- `docs/security/THREAT_MODEL.md`: amenazas y mitigaciones.
- `docs/security/SECURITY_REQUIREMENTS.md`: controles verificables.
- `docs/quality/TEST_STRATEGY.md`: estrategia de pruebas.
- `docs/operations/DEPLOYMENT.md`: despliegue y configuración.
- `docs/operations/BACKUPS_AND_RECOVERY.md`: continuidad y recuperación.
- `docs/business/COMMERCIAL_MODEL.md`: catálogo, precios y promociones.
- `docs/business/LEGAL_COMPLIANCE.md`: cuestiones legales y pendientes.
- `docs/agents/AGENT_WORKFLOW.md`: metodología de desarrollo agéntico.
- `docs/agents/IMPLEMENTATION_RULES.md`: límites y condiciones de implementación.
- `docs/REQUIREMENTS_TRACEABILITY.md`: requisitos, criterios de aceptación y pruebas.
- `docs/OPEN_QUESTIONS.md`: decisiones pendientes.

Puedes modificar esta estructura si justificas una alternativa mejor.

No crees archivos vacíos ni documentos que repitan el mismo contenido sin necesidad.

Cada documento debe tener un propósito inequívoco y referencias cruzadas cuando proceda.

## 23. Trazabilidad y control de cambios

Asigna identificadores estables a los requisitos funcionales, no funcionales y de seguridad.

Cada requisito debe incluir:

- Identificador.
- Descripción.
- Prioridad.
- Estado.
- Justificación.
- Criterios de aceptación.
- Dependencias.
- Riesgos.
- Pruebas asociadas.

Define estados como propuesto, aprobado, implementado, verificado y obsoleto.

No marques un requisito como verificado sin evidencia.

Toda decisión importante debe registrar contexto, alternativas, decisión, consecuencias y estado de aprobación.

La documentación debe distinguir explícitamente:

- Confirmado por el fundador.
- Propuesta pendiente de aprobación.
- Hipótesis que debe validarse.
- Decisión técnica justificada.
- Bloqueo que impide avanzar.

## 24. Método de trabajo para esta primera sesión

Sigue estrictamente estas etapas.

### Etapa A. Inspección

Inspecciona el repositorio y su estado actual antes de modificar archivos.

Identifica si está vacío o contiene código, documentación, configuraciones, dependencias y cambios sin confirmar.

No sobrescribas archivos existentes sin revisar su contenido.

### Etapa B. Investigación

Consulta documentación oficial actualizada para las decisiones técnicas y de seguridad que lo requieran.

Prioriza documentación primaria de los proveedores y estándares oficiales.

Distingue los hechos verificados de las recomendaciones y las hipótesis.

Registra las fuentes relevantes con enlaces y fecha de consulta.

No finjas haber consultado documentación a la que no hayas tenido acceso.

### Etapa C. Análisis

Construye una lista de requisitos, decisiones y riesgos.

Detecta dependencias entre funcionalidades y establece prioridades para el MVP.

Identifica las cuestiones que realmente requieren una respuesta del fundador.

No preguntes por detalles menores que puedan resolverse con una decisión técnica reversible y bien documentada.

### Etapa D. Documentación

Crea los documentos necesarios y verifica que no existan contradicciones entre ellos.

Incluye diagramas Mermaid cuando ayuden a explicar arquitectura, flujos de compra, procesamiento de pagos o entrega de archivos.

Utiliza ejemplos concretos y criterios verificables.

### Etapa E. Auditoría

Comprueba:

- Coherencia entre requisitos y arquitectura.
- Completitud del modelo de datos.
- Seguridad de pagos y descargas.
- Separación de responsabilidades.
- Trazabilidad.
- Viabilidad económica y operativa.
- Ausencia de decisiones comerciales inventadas.
- Ausencia de contradicciones.
- Claridad de las cuestiones pendientes.
- Viabilidad del MVP.

Si es posible, utiliza una revisión independiente mediante un subagente de auditoría con alcance limitado. Verifica sus resultados antes de incorporarlos.

### Etapa F. Entrega

Presenta un informe final con:

1. Archivos creados.
2. Decisiones propuestas.
3. Decisiones que necesitan aprobación.
4. Riesgos críticos.
5. Contradicciones resueltas.
6. Cuestiones pendientes del fundador.
7. Evaluación de preparación para implementar.
8. Orden recomendado de desarrollo.
9. Verificaciones realizadas y sus resultados.

## 25. Límites de esta fase

Durante esta sesión está prohibido:

- Implementar páginas de la tienda.
- Crear el sistema real de autenticación.
- Implementar pagos.
- Crear tablas de producción.
- Desplegar servicios.
- Crear cuentas externas.
- Comprar dominios.
- Generar credenciales.
- Instalar dependencias de la aplicación sin necesidad.
- Modificar archivos existentes de forma destructiva.
- Ejecutar operaciones irreversibles.
- Declarar el producto listo para producción.

La única finalidad de esta sesión es producir una especificación coherente y auditable.

Puedes crear documentación, diagramas y ejemplos ilustrativos, pero no deben confundirse con código de producción.

## 26. Condición final de aceptación

La sesión termina cuando:

- La documentación necesaria existe.
- Los requisitos tienen criterios de aceptación.
- Las decisiones propuestas están diferenciadas de las aprobadas.
- La arquitectura es coherente.
- Los flujos críticos de pago y descarga están especificados.
- Los requisitos de seguridad son verificables.
- El MVP está delimitado.
- Las dependencias externas están identificadas.
- Los riesgos y las preguntas pendientes están documentados.
- Se ha realizado una auditoría de consistencia.
- No se ha comenzado a implementar la aplicación.

No empieces la fase de desarrollo automáticamente.

Entrega el informe final y espera la revisión del fundador.

Tu objetivo no es generar la mayor cantidad de Markdown posible. Tu objetivo es reducir la ambigüedad, anticipar errores y establecer un contrato de trabajo fiable para el desarrollo posterior.