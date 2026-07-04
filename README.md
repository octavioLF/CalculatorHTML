# Calculadora Científica Web

Una calculadora científica construida con HTML, CSS y JavaScript puro. No usa frameworks ni dependencias externas.

El objetivo del proyecto es replicar el comportamiento de una calculadora física real: las operaciones se guardan en memoria y el historial se muestra en una pantalla secundaria conforme se van ingresando los valores.

## Características

- **Pantalla dual:** El número anterior y la operación suben al historial cuando se empieza a escribir el siguiente valor.
- **Operaciones básicas:** Suma, resta, multiplicación y división.
- **Funciones científicas:** Seno, coseno y tangente (en grados), raíz cuadrada, potencia al cuadrado y constante Pi.
- **Corrección por dígito:** Botón de retroceso (⌫) para borrar el último carácter sin perder toda la operación.
- **Limpieza total:** Botón C para reiniciar la calculadora por completo.
- **Sin dependencias:** Funciona directo en el navegador, no necesita servidor local ni compilador.

## Diseño visual

La interfaz usa un enfoque visual moderno con las siguientes decisiones de diseño:

- Fondo con gradiente oscuro en tonos púrpura.
- Efecto glassmorphism en el cuerpo de la calculadora (blur + bordes translúcidos).
- Botones con gradientes, sombras y volumen que simulan profundidad.
- Micro-animación tipo ripple al presionar cada botón.
- Tipografía Inter de Google Fonts para una lectura más limpia.
- Colores diferenciados por tipo de botón: numéricos (oscuros), operadores (dorado), científicos (gris), borrar (naranja), limpiar (rojo) e igual (verde).

## Cómo usarlo

1. Descarga o clona este repositorio.
2. Abre el archivo `Calculadora.html` con doble clic.
3. Se abrirá directamente en tu navegador y estará listo para usarse.

## Tecnologías

- HTML5
- CSS3 (Grid, gradientes, glassmorphism, animaciones)
- JavaScript vanilla
- Google Fonts (Inter)
