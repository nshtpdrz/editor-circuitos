# Editor de Circuitos

Aplicación web de un solo archivo (`editor-circuitos.html`) para armar diagramas de circuitos electrónicos y resolverlos en DC.

**Úsalo en línea:** https://nshtpdrz.github.io/editor-circuitos/

## Uso

Abre `editor-circuitos.html` en el navegador (o el link de arriba). No necesita instalación.

- Coloca componentes desde la paleta (resistencias, fuentes, tierra, capacitores, diodos, LEDs, interruptores, etc.).
- Une terminales con cables; termina un cable sobre otro para crear un nodo.
- **Resolver** calcula voltajes de nodo y corrientes por análisis nodal.
- **Análisis** muestra la ley de Ohm, la 1ra y 2da ley de Kirchhoff y el balance de potencia paso a paso.
- Guarda/abre diagramas en `.json` y exporta a SVG o PNG.

Limitaciones: análisis solo en DC (las fuentes AC se toman como DC) y los transistores aún no se simulan.
