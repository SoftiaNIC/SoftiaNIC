# Instalación del README de perfil de sof.ia

## Organización de GitHub

Copia el contenido de esta carpeta dentro del repositorio especial de perfil:

```text
.github/
└── profile/
    ├── README.md
    ├── INSTRUCCIONES.md
    └── assets/
        ├── brand/
        │   ├── sofia-dark.png
        │   └── sofia-light.png
        ├── comparison.svg
        ├── hero.svg
        ├── metrics.svg
        ├── projects/
            ├── gnomo.webp
            ├── inversiones-valle.webp
            ├── neoark.webp
            ├── sueltalo.webp
            ├── tecnomedia-shop.webp
            └── tecnomedia-studio.webp
        └── services.svg
```

GitHub mostrará automáticamente `profile/README.md` en la página principal de la organización.

## Criterios de mantenimiento

1. Usa `Sof.ia-landding` como fuente principal para contenido institucional, servicios, equipo, proyectos y enlaces.
2. Conserva como componentes gráficos el hero, las métricas, los servicios y la comparación de ingeniería porque definen la identidad visual de la landing. Mantén el texto equivalente dentro de `alt` o bloques desplegables.
3. No publiques información del catálogo interno, precios, datos de demostración ni enlaces marcados con `#` en la landing.
4. Antes de actualizar métricas (`7+`, `150+`, `50+`, `30+`), confirma que continúen vigentes en la landing pública.
5. Optimiza las capturas a WebP y mantenlas locales para que el perfil no dependa del despliegue de la landing.
6. Comprueba los enlaces externos y revisa el perfil tanto en modo claro como oscuro.
7. Si cambia el sistema visual de la landing, actualiza los cuatro SVG sin convertir el resto del README en imágenes rígidas.
