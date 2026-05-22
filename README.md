# Solemne2-Pensamiento-computacional-


-[link](https://editor.p5js.org/dannyy/sketches/_woQAEvP2)

-[link](https://editor.p5js.org/dannyy/full/_woQAEvP2)

foto 

# Información del proyecto
## Nombre del proyecto 
Campo de vibración 
## Autor/a
Daniela Muñoz

# Descripción objetiva 

## ¿Qué es el proyecto? 

El proyecto consiste en un sistema visual dinámico e interactivo desarrollado en p5.js. La obra utiliza una grilla de círculos que cambia constantemente según la interacción del usuario mediante el movimiento del mouse y el uso del teclado.
El sistema genera variaciones de tamaño y composición en tiempo real, produciendo efectos visuales relacionados con el arte cinético.

## ¿Qué se ve en pantalla?

En pantalla se observa una composición modular formada por múltiples círculos distribuidos en una grilla. Las figuras reaccionan continuamente al movimiento del mouse, modificando su tamaño y generando variaciones visuales dinámicas.
Además, el usuario puede cambiar los colores del sistema mediante distintas teclas , alterando el contraste entre fondo y figuras.

## ¿Qué elementos visuales aparecen?

- Grilla modular de círculos.
- Composición geométrica repetitiva.
- Variaciones de tamaño.
- Contraste entre fondo y figuras.
- Cambios cromáticos interactivos.
- Movimiento visual generado mediante variaciones aleatorias.

## ¿Qué inputs utiliza?

- mouseX
- mouseY
- teclado: tecla n, tecla b

## ¿Qué outputs genera?

El sistema genera:
- Cambios de tamaño en tiempo real
- Cambios de color
- Variaciones visuales aleatorias
- Patrones ópticos dinámicos
- Percepción de vibración visual

# Descripción conceptual

## Idea central del proyecto

La idea principal del proyecto es explorar cómo un sistema computacional puede generar percepción de movimiento utilizando repetición, variación e interacción.

## Corriente o referente de diseño

![texto alternativo imagen](https://tk-arte-cinetico.weebly.com/uploads/3/7/1/2/37126569/7082873.jpg?412)

El proyecto dialoga con el arte cinético.
El arte cinético se caracteriza por trabajar con movimiento real o perceptual, utilizando patrones, repeticiones, contrastes y transformaciones visuales para alterar la percepción del espectador.

## Referentes visuales, teóricos e históricos

- Arte cinético: Corriente artística centrada en el movimiento y la percepción visual dinámica.
- Op Art: Uso de patrones geométricos repetitivos para generar ilusiones ópticas y vibración visual.
- Sistemas generativos: Uso de reglas computacionales para producir composiciones variables y no estáticas.

## Principio de diseño explorado

El proyecto explora:
- Repetición modular
- Variación
- Contraste
- Interactividad
- Percepción óptica
- Transformación dinámica

# Input / Output y sistema

## Funcionamiento general del sistema 
- El sistema funciona mediante una estructura de bucles for que generan una grilla de círculos.
- Cada círculo es dibujado mediante una función propia llamada dibujarCirculo().

El comportamiento del sistema cambia según:
- Posición del mouse
- Teclas presionadas
- Variaciones aleatorias

## Reglas del sistema 

 Input:

- El usuario mueve el mouse y presiona teclas.

Proceso:

El sistema:
- Calcula tamaños mediante map()
- Aplica variaciones usando random()
- Evalúa condiciones mediante if
- Actualiza los colores y tamaños de las figuras

 Output:

- El resultado es una composición visual dinámica que cambia continuamente en tiempo real.

## Explicación de la interactividad

- El movimiento horizontal del mouse modifica el tamaño general de los círculos.
- El movimiento vertical cambia el comportamiento de la composición mediante condicionales.
- Las teclas permiten alterar el color del fondo y de las figuras, generando distintos estados visuales del sistema.

## Explicación del código 

Variables: 

- Se utilizan variables para: Almacenar colores, controlar tamaños, guardar variaciones del sistema.

Bucles:
- Se utilizan bucles for para crear una repetición modular de figuras en filas y columnas.

Condicionales:
- Se utilizan estructuras if para modificar el comportamiento visual según la posición del mouse y las teclas presionadas.

Función propia:
- La función: organiza el sistema visual y evita repetir código.

map():
- La función map() transforma la posición horizontal del mouse en distintos tamaños de figuras.

random():
- La función random() genera pequeñas variaciones aleatorias para producir vibración visual y evitar una repetición completamente idéntica.

## Respuesta visual 

Este proyecto toma como referencia el arte cinético para explorar la sensación de movimiento a través de elementos simples y repetitivos. La obra utiliza una grilla de círculos que cambia constantemente mediante variaciones de tamaño, color e interacción, generando una composición que nunca se percibe completamente igual. La intención no fue copiar una obra específica, sino trabajar la idea de movimiento visual y percepción óptica desde un sistema programado en p5.js.
La interacción del usuario es una parte importante del proyecto, ya que el movimiento del mouse y el uso de teclas modifican continuamente el comportamiento visual de la composición. Esto hace que la obra deje de ser una imagen estática y se transforme en un sistema dinámico que responde en tiempo real. A través de reglas simples de programación, el proyecto busca demostrar cómo pequeños cambios pueden producir resultados visuales complejos y relacionados con los principios del arte cinético.









