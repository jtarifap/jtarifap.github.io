# CV de Jorge Tarifa

CV publicado en <https://jtarifap.github.io>.

## Contenido

- `index.html`: CV completo (perfil, experiencia, proyectos propios, formación, cursos e idiomas).
- `style.css`: estilos, fondo animado y adaptación a móvil.

## Criterios

- Sin teléfono público: el contacto se hace por email, GitHub o taridev.com. El número se facilita por email cuando alguien lo pide.
- Un único destino profesional: <https://taridev.com>. No se enlaza la demo de Aura directamente para no enviar a los reclutadores a una versión beta.
- La experiencia profesional va antes que los proyectos propios, para que el CV siga funcionando para empleo y consultoría con terceros.
- Sin precios ni información comercial en el CV.

## Publicar

Esta carpeta es independiente del repositorio de taridev. Para publicarla, súbela al repositorio `jtarifap/jtarifap.github.io` en la rama `main`; GitHub Pages sirve la raíz del repositorio.

```bash
git init
git add index.html style.css README.md
git commit -m "Actualiza CV con proyectos propios y contacto"
git branch -M main
git remote add origin https://github.com/jtarifap/jtarifap.github.io.git
git push -u origin main
```

## Local

Abre `index.html` en cualquier navegador moderno.
