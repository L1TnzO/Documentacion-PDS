# Documentación PDS — sitio con MkDocs Material

Sitio de documentación para A1–A7 usando MkDocs + Material y despliegue automático en GitHub Pages.

## Requisitos

- Python 3.9+ (recomendado)

## Instalar dependencias

En PowerShell:

```powershell
python -m venv .venv ; .\.venv\Scripts\Activate.ps1 ; pip install -U pip ; pip install mkdocs-material mkdocs-minify-plugin mkdocs-git-revision-date-localized-plugin
```

## Servir en local

```powershell
mkdocs serve
```

## Desplegar manualmente (opcional)

```powershell
mkdocs gh-deploy --force
```

Nota: También hay un workflow de GitHub Actions que publica a GitHub Pages al hacer push a main.
