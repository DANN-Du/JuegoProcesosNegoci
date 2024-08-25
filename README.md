# ¿Quién Quiere Ser Millonario?

## Descripción del Juego

"¿Quién Quiere Ser Millonario?" es una adaptación del popular programa de televisión en formato web. Los jugadores responden una serie de preguntas de opción múltiple que aumentan en dificultad y valor monetario. El objetivo es acumular la mayor cantidad de dinero posible respondiendo correctamente a las preguntas.

## Estructura del Juego

El juego está dividido en varias páginas HTML. A continuación, se describe la función de cada página:

### 1. Página de Inicio

**Propósito:** Permite a los jugadores ingresar su nombre y elegir entre ver las instrucciones o comenzar el juego.

- **Campo de texto:** Los jugadores ingresan su nombre.
- **Botones:** 
  - **Instrucciones:** Redirige a la página de instrucciones.
  - **Jugar:** Comienza el juego y redirige a la página principal del juego.

### 2. Página de Instrucciones

**Propósito:** Muestra las reglas del juego y el nombre del jugador que se ha guardado en el almacenamiento local.

- **Campo de texto:** Muestra un mensaje personalizado con el nombre del jugador y las instrucciones del juego.
- **Botón de regresar:** Permite al jugador volver a la página de inicio.

### 3. Página Principal del Juego

**Propósito:** Presenta las preguntas y respuestas del juego. También muestra las opciones para usar comodines o retirarse.

- **Área de Pregunta:** Muestra la pregunta actual y las opciones de respuesta.
- **Botones de respuesta:** Los jugadores seleccionan una respuesta entre las opciones presentadas.
- **Comodines:**
  - **50/50:** Elimina dos opciones incorrectas.
  - **Llamada:** Permite consultar a un amigo.
  - **Público:** Muestra la opinión de la audiencia.
- **Botones de acción:** 
  - **Sí:** Permite al jugador retirarse con el dinero acumulado.
  - **No:** Permite al jugador continuar jugando.

### 4. Página de Resultado

**Propósito:** Se muestra cuando el jugador se rinde o responde incorrectamente.

- **Botones:**
  - **Me Rindo:** Permite al jugador abandonar el juego.
  - **Repetir:** Permite al jugador comenzar el juego nuevamente.

## Cómo Jugar

1. **Inicio:** El jugador ingresa su nombre y elige entre ver las instrucciones o comenzar el juego.
2. **Instrucciones:** Se muestra una breve explicación de cómo jugar y las reglas del juego.
3. **Juego:** El jugador responde a preguntas y gana dinero según la secuencia correcta de respuestas. Puede usar comodines o retirarse en cualquier momento.
4. **Resultado:** Si el jugador se rinde o responde incorrectamente, se muestra una página de resultado con opciones para volver a empezar o terminar el juego.

## Reglas del Juego

- **Preguntas y Respuestas:** Cada pregunta tiene cuatro opciones de respuesta. El jugador debe seleccionar la correcta para avanzar.
- **Comodines:** El jugador tiene tres comodines que pueden usarse una vez por juego.
- **Retiro:** El jugador puede retirarse en cualquier momento y llevarse el dinero acumulado.
- **Pérdida de Ganancias:** Una respuesta incorrecta puede reducir las ganancias a niveles preestablecidos.

## Requisitos Técnicos

El juego está desarrollado en HTML y JavaScript, utilizando almacenamiento local para guardar el nombre del jugador y la lógica del juego.

---

Para jugar, abre el archivo `Index.html` en un navegador web y sigue las instrucciones en pantalla.
