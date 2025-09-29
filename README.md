# Proyecto: Planta de Tubos Recolectores

Resumen rápido

Este repositorio contiene una presentación interactiva en HTML/CSS/JS que describe un proyecto para la instalación de una planta productora de tubos recolectores de sangre. Está diseñada para utilizarse como sitio estático (presentación o entrega de proyecto).

Cambios recientes

- Eliminada la sección de "Contacto" y su enlace en la navegación (se removió el formulario y el enlace del menú).
- Limpieza menor del HTML: se eliminó el comentario que marcaba la sección de contacto.

Cómo probar localmente

1. Abrir el archivo `index.html` en tu navegador favorito (doble clic o arrastrar al navegador).

2. Si preferís servirlo por un servidor HTTP (recomendado para algunas APIs o CORS):

- Con Python 3:

```powershell
# desde la carpeta del proyecto
python -m http.server 8000
# luego abrir http://localhost:8000
```

- Con Node.js (si tenés http-server instalado):

```powershell
npx http-server -c-1
# o
npx serve
```

Notas

- La página usa Tailwind CDN y Chart.js; necesitás conexión a internet para cargar esos recursos si no los servís localmente.
- Si querés reactivar un formulario de contacto, reemplazá el endpoint de Formspree en el HTML o integrá un backend.

Contacto del repositorio

Para cambios en el repositorio, podés crear una rama y un Pull Request hacia `interactive`.
