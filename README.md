# Sistema de Llamadas para Camareros

Frontend estático para el sistema de llamadas de camareros. Este proyecto está diseñado para ser alojado en GitHub Pages.

## Uso

Accede a la página con los parámetros de URL:
- `mesa`: Número de la mesa (ej: 1, 2, 3...)
- `rest`: ID del restaurante (ej: rest_001)

Ejemplo: `https://axeaa24.github.io/sistema-llamadas-camareros/?mesa=1&rest=rest_001`

## Configuración

Para personalizar el webhook y la clave API:
1. Edita el archivo `index.html`
2. Busca las líneas:
   ```javascript
   const URL_WEBHOOK = 'https://axeaa.app.n8n.cloud/webhook/llamar-camarero';
   const API_KEY = 'df9ea6cd-c6d1-4ae2-9836-139a70d2bca1';
