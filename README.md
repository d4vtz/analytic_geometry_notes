# Geometría Analítica — notas para bachillerato

Proyecto LaTeX modular. La primera unidad cubre plano cartesiano, distancia,
punto medio, división interna de segmentos y aplicaciones geométricas.

## Compilación

Se requiere XeLaTeX o LuaLaTeX. Desde la carpeta del proyecto:

```bash
latexmk -xelatex main.tex
```

Para limpiar archivos auxiliares:

```bash
latexmk -c
```

## Estructura

- `main.tex`: documento principal.
- `geometria.sty`: diseño, colores, entornos y configuración gráfica.
- `unidades/unidad01.tex`: contenido de la primera unidad.

El paquete incluye entornos para definiciones, notación, teoremas, lemas,
corolarios, proposiciones, afirmaciones, preguntas, ejemplos, ejercicios,
problemas, algoritmos, demostraciones, soluciones, observaciones, pistas,
intuición, propiedades y fórmulas clave.
