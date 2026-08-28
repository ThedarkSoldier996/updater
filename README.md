# NovaPlay - Central de Actualizaciones y Configuración

Este repositorio actúa como el nodo central para la distribución de actualizaciones y la gestión de configuraciones remotas para el ecosistema **NovaPlay**.

## 📂 Estructura del Repositorio

### 📦 Binarios (APKs)
Distribución directa de los instaladores de la aplicación para diferentes canales:

*   **`novaplay.apk`**: Versión estable recomendada para todos los usuarios.
*   **`novaplaybeta.apk`**: Versión de desarrollo con las últimas funciones y optimizaciones experimentales.
*   **`novapanel.apk`**: Herramienta de gestión y administración.

### ⚙️ Canales de Actualización (JSON)
Archivos que controlan el motor de actualización inteligente de la app:

*   **`updatestable.json`**: Metadatos y registro de cambios para la rama de producción.
*   **`updatebeta.json`**: Metadatos y changelog para la rama de pruebas (beta).
*   **`panelupdater.json`**: Control de versiones para la aplicación administrativa.

### 🔔 Configuración Dinámica
Gestión remota de funciones en tiempo real sin necesidad de reinstalar la app:

*   **`eventos.json`**: Controla los mensajes informativos y anuncios dinámicos de la interfaz.
*   **`mantenimiento.json`**: Permite activar el modo de servicio o mantenimiento global.
*   **`notifications.json`**: Gestión de notificaciones remotas (Push-like) enviadas a los usuarios.

---

## 🛠️ Notas Técnicas

1.  **Distribución CDN**: Todos los recursos se sirven a través del CDN de GitHub Raw para garantizar alta disponibilidad y baja latencia a nivel mundial.
2.  **Integridad**: El motor de la aplicación valida el `version_code` contenido en los archivos JSON antes de iniciar cualquier proceso de descarga o instalación.
3.  **Seguridad**: Los binarios alojados en este repositorio son firmados por el autor original para garantizar su autenticidad.

## ⚖️ Aviso Legal

Este repositorio contiene software propietario y recursos técnicos destinados únicamente al ecosistema NovaPlay. Queda prohibida la redistribución o modificación de los archivos JSON y binarios sin autorización expresa.

Desarrollado con ❤️ por ThedarkSoldier996

© 2010 - 2026 M.S.G.T SOLUTIONS. 
