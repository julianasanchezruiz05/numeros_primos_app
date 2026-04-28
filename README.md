🌌 PRIME.SYS - Verificador Neón de Números Primos

Un aplicativo web moderno y futurista diseñado para identificar números primos, combinando una estética Cyberpunk con una lógica matemática eficiente.

📝 Descripción

Este proyecto es una herramienta interactiva de una sola página (SPA) que permite a los usuarios verificar si un número entero positivo es primo o no. El sistema utiliza un algoritmo de complejidad optimizada para ofrecer resultados instantáneos, acompañados de una experiencia visual inmersiva.

👤 Créditos

Desarrolladora: Juliana Sanchez

Asistencia: Inteligencia Artificial (IA)

🚀 Características Principales

Estética Neón: Interfaz diseñada con colores vibrantes, tipografías futuristas (Orbitron, Rajdhani) y efectos de desenfoque de fondo (backdrop-filter).

Fondo Animado: Sistema de partículas de números flotantes que se mueven continuamente por la pantalla.

Validación Inteligente:

Detecta si la entrada es un número entero.

Maneja casos especiales (0, 1 y números negativos).

Proporciona retroalimentación educativa (muestra un divisor si el número no es primo).

Feedback Visual Dinámico:

Éxito (Número Primo): Explosión de confeti neón y resaltado en verde esmeralda.

Error (No es Primo/Inválido): Animación de sacudida (shake) y resaltado en rojo carmesí.

🛠️ Tecnologías Utilizadas

HTML5: Estructura semántica del aplicativo.

Tailwind CSS: Framework de estilos utilizado para el diseño responsivo y efectos neón.

JavaScript (Vanilla): - Lógica del algoritmo de primalidad ($O(\sqrt{n})$).

Manipulación del DOM para animaciones y estados.

Generación dinámica de elementos del fondo.

Canvas-Confetti: Librería externa para la animación de celebración.

📖 Instrucciones de Uso

Abra el archivo primos_neon.html en cualquier navegador web moderno.

Observe la etiqueta de autoría en la parte superior derecha.

Ingrese un número en el campo central con la etiqueta "INGRESAR SECUENCIA NUMÉRICA".

Presione el botón "Iniciar Escaneo" o presione la tecla Enter.

Disfrute de la animación resultante y lea la descripción del análisis.

🧮 Detalles del Algoritmo

El script utiliza una técnica de optimización que:

Elimina rápidamente los números pares y los múltiplos de 3.

Itera desde 5 hasta la raíz cuadrada del número ingresado ($\sqrt{n}$), saltando de 6 en 6 ($6k \pm 1$).
Esto permite procesar números de hasta 15 dígitos sin congelar la interfaz del navegador.

Prototipo desarrollado con fines educativos y experimentales.