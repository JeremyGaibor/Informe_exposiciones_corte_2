# Informe de Exposición 2do Corte - Defensa del PFC

Este repositorio contiene el informe en formato LaTeX sobre las exposiciones de defensa del PFC (Proyecto de Fin de Carrera), correspondiente al 2do corte.

## Contenido

- `informe.tex` — Documento fuente en LaTeX con el informe completo.
- `informe.pdf` — (generado al compilar) versión en PDF lista para entregar.

## Estructura del documento

El informe incluye:

1. **Encabezado** con datos institucionales y del autor.
2. **Grupo Pacheco, Carpio, Cando y Álvarez** — resumen de la exposición y tabla de participación.
3. **Grupo Castro, Luna, Bedón y Juliana** — resumen de la exposición y tabla de participación.
4. **Grupo Farinango, Villamarín, Harold e Isaías** — resumen de la exposición y tabla de participación.
5. **Conclusión** general comparando los tres grupos.

## Requisitos

Para compilar el documento necesitas una distribución de LaTeX instalada, por ejemplo:

- [TeX Live](https://www.tug.org/texlive/) (Linux/Windows/Mac)
- [MiKTeX](https://miktex.org/) (Windows)
- [Overleaf](https://www.overleaf.com/) (en línea, no requiere instalación)

### Paquetes utilizados

- `babel` (español)
- `geometry` (márgenes)
- `booktabs` (tablas)
- `array` (tablas)

## Cómo compilar

### Opción 1: Línea de comandos (Linux/Mac/Windows con TeX Live o MiKTeX)

```bash
pdflatex informe.tex
```

Ejecuta el comando dos veces si el documento tiene referencias cruzadas o tabla de contenido (no es el caso aquí, pero es buena práctica).

### Opción 2: Overleaf

1. Sube el archivo `informe.tex` a un nuevo proyecto en Overleaf.
2. Overleaf compilará automáticamente y mostrará el PDF.

### Opción 3: Editor local (TeXstudio, VS Code + LaTeX Workshop, etc.)

Abre `informe.tex` y usa el botón de compilar/build de tu editor.

## Personalización

- **Salto de página:** agrega `\newpage` donde quieras que una sección comience en una página nueva (por ejemplo, antes de cada grupo).
- **Márgenes:** ajusta el valor `margin=2.5cm` en `\usepackage[margin=2.5cm]{geometry}`.
- **Tablas:** las tablas usan `booktabs` (`\toprule`, `\midrule`, `\bottomrule`) para un estilo limpio sin líneas verticales.

## Licencia

Uso académico — Universidad Técnica Estatal de Quevedo.
