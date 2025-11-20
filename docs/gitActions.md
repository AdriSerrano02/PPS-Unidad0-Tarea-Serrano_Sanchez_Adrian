# GitHub Actions - Automatización de Documentación

## Configuración del Workflow

### Archivo: `.github/workflows/CreacionDocumentacion.yml`

El workflow configurado realiza las siguientes acciones:

1. **Trigger**: Se ejecuta automáticamente en cada push a la rama `main`
2. **Permisos**: Configura los permisos necesarios para GitHub Pages
3. **Steps**:
   - Checkout del código
   - Configuración de Python 3.x
   - Instalación de dependencias (mkdocs)
   - Despliegue automático de la documentación

### Comprobación del funcionamiento

1. Realicé un push al repositorio
2. Verifiqué en la pestaña "Actions" de GitHub que el workflow se ejecutó correctamente
3. Confirmé que se creó la rama `gh-pages` automáticamente

![Imagen Workflows](/imagenes/workflow.png)
