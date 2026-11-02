# # Sprint 7: Programación Modular, Estructuras de Datos y Algoritmia en Python

Este repositorio contiene la resolución práctica de los desafíos planteados en el **Sprint 7**, estructurado en tres niveles de complejidad creciente. Los proyectos abordan desde la lógica de control básica y la gestión de flujos hasta el procesamiento avanzado de archivos, análisis de datos con pandas y la modularidad orientada a la resolución de problemas reales de negocio, salud y ciberseguridad.

## 📋 Contenido del Sprint

### 🔹 Nivel 1: Formularios y Segmentación Básica
*   **Ejercicio 1: Selección de Personal (RRHH):** Un sistema modular de inscripción y clasificación de candidatos utilizando flujos interactivos, validación estricta de datos (tipos, límites) y algoritmos de ordenación personalizada multinivel (prioridad y puntuación).
*   **Ejercicio 2: Segmentación por Riesgo de Cesta de Compra (Marketing):** Análisis del comportamiento de navegación y abandono de carritos para calcular un índice de riesgo de fuga, enriqueciendo los perfiles mediante pandas DataFrames y generando respuestas automatizadas para estrategias de retargeting.

### 🔹 Nivel 2: Triaje Médico y Evaluación de Seguros
*   **Ejercicio 1: Triaje y Priorización de Pacientes (HealthTech):** Procesamiento de strings desestructurados procedentes de sistemas médicos, estandarización de síntomas mediante técnicas de limpieza de cadenas, y priorización automatizada según la gravedad acumulada.
*   **Ejercicio 2: Clasificación de Clientes de Seguros (InsurTech):** Cálculo modular del precio de pólizas ajustado por edad y evaluación del riesgo de fraude, identificando de manera inteligente los casos de alta prioridad para revisión manual mediante DataFrames.

### 🔹 Nivel 3: Algoritmia Avanzada y Procesamiento de Archivos
*   **Ejercicio 1: Generador de Contraseñas Seguras (Ciberseguridad):** Herramienta parametrizable para generar credenciales de alta seguridad. Integra el uso de selección aleatoria avanzada con `numpy` asegurando la presencia mínima obligatoria de caracteres requeridos y barajado estocástico.
*   **Ejercicio 2: Procesador de Datos Deportivos (Data Analytics):** Un flujo completo de lectura de archivos (` historic partits.txt`), parsing de delimitadores, agregación de estadísticas (goles, victorias, empates, derrotas) y cálculo de la tabla general con asignación de puntos oficiales.

---

## 🛠️ Tecnologías y Librerías Utilizadas

*   **Lenguaje:** Python 3.x
*   **Análisis de Datos:** `pandas`
*   **Generación Estocástica:** `numpy` (generación de números aleatorios y muestras)
*   **Presentación:** `IPython.display` para visualización enriquecida de tablas dentro de entornos Jupyter/Colab.

---

## 🚀 Principios de Diseño Aplicados

1.  **Modularidad (DRY):** Cada tarea compleja ha sido desgranada en pequeñas subfunciones de responsabilidad única (SRP), facilitando las pruebas unitarias y el mantenimiento.
2.  **Validación de Datos Defensiva:** Implementación de bloques `try-except`, control de tipos de datos, límites y formatos (como validación de números telefónicos o puntuaciones dentro de rangos estrictos).
3.  **Algoritmia Eficiente:** Uso de estructuras de datos adecuadas (tuplas para inmutabilidad, diccionarios para búsquedas en tiempo constante $O(1)$ y DataFrames para el análisis tabular).
