|| El Panel de Control Domótico - Smart Life Admin

Este proyecto es una interfaz personalizada y autoadministrada para la gestión de dispositivos inteligentes compatibles con el ecosistema **Tuya / Smart Life**. El sistema está diseñado para ser ligero, funcional y se despliega de forma gratuita a través de **GitHub Pages**.

|| Sus Características

*   **Administración Total:** Control centralizado de luces, enchufes y sensores.
*   **Costo Cero:** Alojamiento gratuito mediante GitHub Pages.
*   **Interfaz Responsiva:** Optimizado para su uso en computadores, tablets y smartphones.
*   **Basado en:** [ndg63276/smartathome](https://github.com/ndg63276/smartathome).

|| Las Tecnologías Utilizadas

*   **Frontend:** HTML5, CSS3, JavaScript.
*   **API:** Tuya Cloud SDK / IoT Platform.
*   **Hosting:** GitHub Pages.
*   **Presupuesto Mensual:** **$0 CLP**.

|| La Estructura del Repositorio

*   `/index.html`: Punto de entrada principal del panel (anteriormente `safe.html`).
*   `/css`: Estilos personalizados para la interfaz.
*   `/js`: Lógica de conexión con la API de Smart Life.
*   `/assets`: Iconos y recursos visuales.

|| La Configuración de Administración

Para que el panel funcione con tus propios dispositivos, es necesario configurar las credenciales en el portal de desarrolladores de Tuya:

1.  Obtener el `Access ID` y `Client Secret` desde [Tuya IoT Platform](https://iot.tuya.com/).
2.  Vincular la cuenta de la App Smart Life en la sección "Cloud".
3.  Actualizar las variables en el archivo de configuración correspondiente dentro de este repositorio.

## Acerca de la Seguridad

> [!IMPORTANT]  
> Este panel es de uso personal. Si el repositorio es público, **nunca** subas tus llaves API directamente al código. Se recomienda el uso de repositorios privados o la implementación de un proxy de autenticación.

---
**Administrado por:** Jonathan V. Apiolaza  
**Ubicación:** Quilpué, Chile 🇨🇱  
**Última actualización:** Mayo 2026
