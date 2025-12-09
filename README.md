# 🚀 SD_ANALYTICS

---

## 🏗️ Descripción del Proyecto: Juego Doodler en JavaScript

Este proyecto demuestra la incrustación de una aplicación web frontend tradicional (HTML, CSS, JavaScript) dentro de un framework de aplicación de datos de Python (Streamlit). La aplicación funciona como una calculadora simple.

### ⚙️ Funcionamiento y Arquitectura

La aplicación sigue el modelo de desarrollo web tradicional, combinando cuatro tecnologías clave:

### 1. Estructura (HTML) 🏗️

Proporciona el esqueleto de la calculadora:
* **Contenedor principal:** Un `div` para agrupar y centrar los elementos.
* **Entradas de usuario:** Dos campos de texto (`<input type="number">`) para los operandos (**firstNumber** y **secondNumber**).
* **Selector de Operación:** Un menú desplegable (`<select id="operator">`) para elegir la operación (**+, -, *, /**).
* **Interacción:** Un botón (`<button id="calculate">`) que inicia el proceso.
* **Salida:** Un párrafo (`<p id="result">`) para mostrar el resultado o mensajes de error.

### 2. Estilo (CSS) ✨

El CSS se aplica para una presentación visual **limpia** y **responsive** dentro del entorno Streamlit:
* **Diseño:** Centrado, bordes redondeados y una sombra sutil.
* **Consistencia:** Estilo uniforme aplicado a entradas, selector y botón.
* **Énfasis:** El botón "Calculate" se destaca con un color de fondo verde (`#4CAF50`).

### 3. Lógica (JavaScript) 🧠

El motor funcional que maneja la interacción y realiza los cálculos:
* **Captura de DOM:** Localiza los elementos HTML por su `ID`.
* **Función `calculate()`:** Se ejecuta al hacer clic, convierte entradas a números (`parseFloat`), **valida** las entradas (`isNaN`), y usa una sentencia `switch` para aplicar la operación.
* **Manejo de Excepciones:** Incluye lógica para la **división por cero**.
* **Manejador de Eventos:** El método `addEventListener('click', calculate)` enlaza el clic del botón a la ejecución de la función.


## 🛠️ Stack de Tecnologías y Herramientas

| Tecnología | Rol en el Proyecto |
| :--- | :--- |
| **HTML5** | Estructura los elementos del juego. |
| **CSS3** | Define el aspecto visual y el diseño. |
| **JavaScript** | Implementa la lógica de movimiento y la interactividad. |

---
