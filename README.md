# Proyecto: Trading Algorítmico con Aprendizaje por Refuerzo usando PPO
Este proyecto se centra en el desarrollo de un bot de trading algorítmico utilizando la técnica de Proximal Policy Optimization (PPO), un algoritmo avanzado de aprendizaje por refuerzo profundo. Se explora la aplicación de PPO en mercados financieros, demostrando su capacidad para tomar decisiones de compra y venta en un entorno dinámico como el mercado de valores.

## Contenido del Proyecto
### *1. Introducción a PPO*
- *Conceptos Básicos*: PPO es una técnica derivada de los Policy Gradient Methods, ampliamente utilizada en el aprendizaje por refuerzo debido a su estabilidad y eficiencia.
- *Aplicaciones en la Industria*: PPO es popular en el desarrollo de videojuegos y procesamiento en 3D, gracias a su capacidad para adaptarse rápidamente a cambios y mitigar los efectos de la incertidumbre.
- *Función de Coste*: Se utiliza la función L^{CLIP}(\theta) que optimiza el modelo, balanceando la exploración y explotación en entornos volátiles como los mercados financieros.
### *2. Configuración del Entorno*
- *Instalación de Librerías*: Se listan las librerías necesarias como gymnasium, stable-baselines3, pybroker, numpy, matplotlib, y pandas.
- *Definición de la Clase de Entorno*: Se crea un entorno personalizado para el trading utilizando OpenAI GYM, permitiendo la simulación de operaciones de compra y venta en diferentes mercados.
- *Funciones Auxiliares*: Se desarrollan funciones como dataset_loader para la carga de datos y render_all para la visualización del rendimiento del bot.
### *3. Implementación del Bot de Trading*
- *Creación del Entorno de Trading*: Se implementa la clase StockTradingEnv que modela el entorno de trading, incluyendo la lógica para ejecutar acciones, calcular recompensas, y actualizar el estado del bot.
- *Entrenamiento del Modelo*: Se entrena el modelo utilizando datos históricos de acciones como Apple (AAPL) desde 2019 hasta 2023. Se establecen parámetros como el balance inicial, comisiones, y costos de deslizamiento.
- Validación del Modelo: Se valida el modelo utilizando datos recientes (2023-2024) para evaluar su desempeño en escenarios reales.
### *4. Pruebas Adicionales*
- *Evaluación en BTC-USD*: Se realiza una prueba adicional en el par Bitcoin-Dólar (BTC-USD), ajustando los parámetros del entorno para manejar el alto valor y volatilidad de Bitcoin. Se analizan los resultados obtenidos y se comparan con la realidad del mercado.
### Herramientas y Lenguajes de Programación Utilizados
- *Python*: Lenguaje principal para la implementación del modelo y manipulación de datos.
- *Stable-Baselines3*: Biblioteca utilizada para la implementación de algoritmos de aprendizaje por refuerzo.
- *Gymnasium*: Entorno utilizado para crear y gestionar las simulaciones de trading.
- *PyBroker*: Biblioteca para acceder a datos financieros históricos y en tiempo real.
- *Matplotlib*: Utilizado para la visualización de resultados y análisis de rendimiento.
Propósito del Proyecto

Este proyecto tiene como objetivo demostrar las capacidades de PPO en la creación de bots de trading algorítmico que operan en mercados financieros volátiles. Se busca ilustrar cómo técnicas avanzadas de aprendizaje por refuerzo pueden ser aplicadas para tomar decisiones informadas y maximizar los beneficios en escenarios reales.

Este README proporciona un resumen detallado del desarrollo del bot de trading, destacando las competencias en aprendizaje por refuerzo, análisis de datos, y la implementación de modelos en entornos de simulación financiera.