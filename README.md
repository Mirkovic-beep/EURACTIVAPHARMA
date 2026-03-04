# EURACTIVA PHARMA - Landing temporal

Este repositorio contiene una landing estática "En construcción" para `euractivapharma.es`.

## Despliegue automático en GitHub Pages

El repo queda preparado para desplegar automáticamente con GitHub Pages mediante GitHub Actions:

- Workflow: `.github/workflows/deploy-pages.yml`
- Se ejecuta en pushes a `main`, `master` y `work` (rama actual), y también manualmente (`workflow_dispatch`).
- Publica el contenido estático del repositorio completo.

### Qué activar en GitHub

1. En GitHub, entra en **Settings → Pages**.
2. En **Build and deployment**, selecciona **Source: GitHub Actions**.
3. Haz push a la rama configurada (`work`, `main` o `master`) y el despliegue se lanzará automáticamente.

## Estructura

- `index.html` — Página principal en construcción.
- `styles.css` — Estilos de la landing.
- `logo-euractiva.png` — Logo corporativo proporcionado.
