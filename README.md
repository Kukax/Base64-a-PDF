# Base64 a PDF

Página extremadamente simple para convertir código Base64 a PDF. 100% en el navegador, sin backend, sin dependencias.

## Uso

1. Abre `index.html` en tu navegador (doble clic).
2. Pega el código Base64 en el textarea. Acepta:
   - Base64 puro: `JVBERi0xLjQK...`
   - Data URI: `data:application/pdf;base64,JVBERi0xLjQK...`
3. Click en **Convertir a PDF** para ver la vista previa.
4. Click en **Descargar PDF** para guardar como `documento.pdf`.

## Características

- Conversión instantánea con `atob` → `Blob` → `URL.createObjectURL`
- Vista previa en `iframe`
- Validación básica de Base64
- Funciona offline

## Demo

Solo abre `index.html`. No requiere instalación ni build.

## Licencia

MIT
