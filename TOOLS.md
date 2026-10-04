# TOOLS.md — Herramientas disponibles

> ⚠️ No incluyas credenciales, tokens ni claves aquí. Los valores predeterminados hacen referencia a cuentas verificadas sin exponer identificadores internos.

---

## Zapier MCP — Google Calendar

**Cuenta predeterminada:** carolperdomo885esp@gmail.com (única cuenta conectada)

| Herramienta | Tipo | ¿Para qué sirve? | ¿Cuándo usarlo? |
|---|---|---|---|
| **Find Events** | Lectura | Buscar eventos en un calendario específico. Soporta filtros por fecha, asistente, tipo de evento y búsqueda por texto. | Para consultar eventos próximos, revisar la agenda del día/semana, o buscar eventos específicos. |
| **Retrieve Event by ID** | Lectura | Obtener un evento concreto usando su ID interno. | Cuando necesitas los detalles exactos de un evento ya identificado. |
| **Find Busy Periods** | Lectura | Ver los bloques ocupados en un calendario en un rango de fechas. | Para saber si tienes tiempo disponible antes de agendar algo nuevo. |
| **Find Calendars** | Lectura | Listar todos tus calendarios (propios y suscritos). | Para explorar calendarios disponibles o elegir uno diferente al agendar. |
| **Get Calendar Information** | Lectura | Obtener metadatos de un calendario concreto. | Para ver detalles de un calendario (permisos, descripción, etc.). |
| **Create Detailed Event** | Escritura | Crear un evento completo: título, descripción, ubicación, fecha, asistentes, recordatorios, color, visibilidad. | Para agendar reuniones, citas, viajes o cualquier evento con todos los detalles. |
| **Quick Add Event** | Escritura | Crear un evento rápido desde una descripción en lenguaje natural (ej: "Cena el viernes a las 8pm"). | Para agendar algo rápido sin rellenar todos los campos. |
| **Update Event** | Escritura | Modificar un evento existente: título, fecha, descripción, asistentes, etc. | Para cambiar detalles de un evento ya agendado. |
| **Delete Event** | Escritura | Eliminar un evento del calendario. | Cuando un evento ya no es necesario. |
| **Add Attendee(s)** | Escritura | Añadir asistentes por email a un evento existente. | Para invitar a más personas a un evento ya creado. |
| **Remove Attendee(s)** | Escritura | Quitar asistentes de un evento existente. | Para cancelar la invitación de alguien. |
| **Move Event** | Escritura | Mover un evento de un calendario a otro. | Para reorganizar eventos entre calendarios personales y compartidos. |
| **Create Calendar** | Escritura | Crear un nuevo calendario. | Para separar temas (trabajo, personal, viajes, etc.). |

> **Valor predeterminado:** El calendario principal (`carolperdomo885esp@gmail.com`) es la cuenta por defecto. Si hay más calendarios conectados, se puede elegir cuál usar en cada acción.

---

## Zapier MCP — Google Docs

**Cuenta predeterminada:** carolperdomo885esp@gmail.com (única cuenta conectada)

| Herramienta | Tipo | ¿Para qué sirve? | ¿Cuándo usarlo? |
|---|---|---|---|
| **Find a Document** | Lectura | Buscar un documento por nombre en Google Drive. | Para localizar un documento existente antes de leerlo o editarlo. |
| **Get Document Content** | Lectura | Obtener el contenido completo de un documento por su ID. | Para leer o extraer el texto de un documento (útil en análisis, resúmenes, o revisiones). |
| **Get Document Tabs Content** | Lectura | Obtener contenido de un documento incluyendo sus pestañas/tabs. | Para documentos con múltiples secciones o tabs. |
| **Find Text in Document** | Lectura | Buscar texto dentro de un documento y obtener sus posiciones. | Para localizar términos específicos dentro de un doc largo. |
| **Create Document From Text** | Escritura | Crear un documento nuevo a partir de texto plano o HTML básico. | Para crear documentación, guías, notas o informes desde cero. Soporta formato básico. |
| **Create Document From Template** | Escritura | Crear un documento basado en una plantilla existente, reemplazando variables como `{{nombre}}`. | Para generar documentos estandarizados (informes, cartas, formularios) desde una plantilla. |
| **Upload Document** | Escritura | Subir un archivo desde otro servicio y convertirlo a formato Google Doc. | Para importar documentos desde otras fuentes. |
| **Append Text to Document** | Escritura | Añadir texto al final de un documento existente. | Para agregar contenido nuevo sin abrir el doc manualmente. |
| **Insert Text** | Escritura | Insertar texto en una posición específica dentro de un documento. | Para añadir contenido en medio del documento, no solo al final. |
| **Find and Replace Text** | Escritura | Buscar y reemplazar texto en un documento, con opción de coincidir mayúsculas. | Para corregir o actualizar términos en todo el documento. |
| **Format Text** | Escritura | Aplicar formato (negrita, color, enlaces, tamaño, fuente) a un rango de texto por posición. | Para estilizar contenido existente sin editar manualmente. |
| **Insert Image** | Escritura | Insertar una imagen desde URL en una posición específica. | Para añadir gráficos, logos o capturas a un documento. |
| **Replace Image** | Escritura | Reemplazar una imagen existente por otra nueva. | Para actualizar gráficos o diagramas en un documento. |
| **Update Document Properties** | Escritura | Cambiar propiedades de página: color de fondo, márgenes, tamaño, encabezados. | Para ajustar el diseño o formato general de un documento. |

---

## Cómo usar estas herramientas

Puedes pedirme directamente acciones como:

- *"Nova, ¿qué tengo en el calendario esta semana?"*
- *"Agenda una reunión el jueves a las 3pm"*
- *"Crea un documento llamado Guía de inicio con este contenido..."*
- *"Busca el documento X y dime qué dice"*
- *"Añade al evento de ayer la nota de no olvidar el postre"*
- *"¿Tengo tiempo libre mañana por la tarde?"*
- *"Muéveme el evento de la cena al calendario personal"*

> Los valores predeterminados ya están configurados para usar tu cuenta principal. No necesitas especificar la cuenta cada vez a menos que quieras usar otra diferente.

---

*Última actualización: 4 de octubre de 2026 — Nova 💡*