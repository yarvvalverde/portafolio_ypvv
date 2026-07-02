# Portafolio profesional - Yarlín Vargas

Sitio web construido con Quarto para documentar proyectos, publicaciones y herramientas profesionales en investigación aplicada, estadística y ciencia de datos.

## Estructura

```text
.
├── _quarto.yml
├── index.qmd
├── sobre-mi.qmd
├── proyectos.qmd
├── publicaciones.qmd
├── herramientas.qmd
├── cv.qmd
├── contacto.qmd
├── proyectos/
│   ├── olap-brecha-universitaria.qmd
│   ├── olap-caracterizacion-2025.qmd
│   ├── olap-situacion-laboral-graduados.qmd
│   ├── auditoria-calidad-datos.qmd
│   ├── generador-graficos-pen.qmd
│   └── apps-shiny.qmd
├── assets/img/
├── docs/
└── .github/workflows/publish.yml
```

## Cómo verlo localmente

1. Instalar Quarto: https://quarto.org
2. Abrir la carpeta del proyecto en RStudio o VS Code.
3. Ejecutar:

```bash
quarto preview
```

## Cómo publicarlo en GitHub Pages

1. Crear un repositorio en GitHub, por ejemplo: `portafolio-yarlin`.
2. Subir todos los archivos de esta carpeta.
3. En GitHub, entrar a **Settings > Pages**.
4. En **Build and deployment**, seleccionar **GitHub Actions**.
5. Hacer un commit en la rama `main`.
6. El workflow `.github/workflows/publish.yml` renderiza el sitio y lo publica.

## Ajustes antes de publicar

Reemplazar los enlaces de ejemplo en:

- `_quarto.yml`: LinkedIn, GitHub, repo-url, site-url.
- `contacto.qmd`: LinkedIn y GitHub reales.
- `cv.qmd`: verificar fechas y datos de contacto.
- `docs/CV_Yarlin_Vargas_Actualizado.docx`: revisar que esté final.

## Nota de confidencialidad

Este portafolio usa descripciones profesionales y enlaces públicos. No debe incluir bases de datos internas, documentos confidenciales ni información institucional no publicada.
