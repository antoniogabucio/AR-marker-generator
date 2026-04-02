# AR-marker-generator
Tool to generate simple markers to AR (augmented reality) based in simple images / herramienta para crear marcadores para realidad aumentada basados en imágenes simples
# 🛠️ Generador de Marcadores WebAR (Optimizado para AR.js)

Este repositorio contiene una herramienta web interactiva diseñada para la creación y optimización de patrones de visión artificial (`.patt`). Es una herramienta de soporte metodológico para la implementación de experiencias de Realidad Aumentada (WebAR) basadas en el reconocimiento de imágenes.

## ✍️ Información del Autor

* **Autor:** Antonio Gabucio López
* **ORCID:** [0000-0001-6000-9937](https://orcid.org/0000-0001-6000-9937)

## 📋 Descripción Técnica

La herramienta automatiza el proceso de adecuación de imágenes de entrada para maximizar la eficiencia de lectura del motor de AR.js. El algoritmo integrado realiza las siguientes operaciones:

1. **Transformación de Color:** Convierte la imagen original a escala de grises.
2. **Ajuste de Contraste:** Aplica un filtro de alto contraste (150%) para definir bordes nítidos.
3. **Pixelación Estructural:** Reduce y rasteriza la imagen a una matriz estandarizada de 16x16 píxeles (resolución interna requerida por AR.js).
4. **Codificación:** Utiliza la librería de entrenamiento para generar la matriz de texto del archivo `.patt`.

## 🚀 Instrucciones de Uso

Puede utilizar la herramienta directamente desde el navegador a través de GitHub Pages:
**[AÑADIR AQUÍ EL ENLACE A TU GITHUB PAGES DEL GENERADOR]**

1. Haga clic en **Seleccionar archivo** y cargue una imagen (preferiblemente cuadrada y con formas claras).
2. La herramienta generará automáticamente una previsualización del marcador con su borde reglamentario.
3. Haga clic en **Descargar Marcador (PNG)** para obtener la imagen lista para imprimir.
4. Haga clic en **Descargar Patrón (.PATT)** para obtener el archivo de seguimiento necesario para el código HTML (`<a-marker>`).

## 🔗 Proyecto Principal Vinculado

Esta herramienta fue desarrollada como instrumento metodológico para el siguiente proyecto de Realidad Aumentada interactiva:
* **Visualización y Control del Ritmo Cardíaco en WebAR:** [AÑADIR AQUÍ EL ENLACE A TU REPOSITORIO PIN-CORAZON]

## 📚 Atribuciones Tecnológicas

* **Motor de Codificación:** Integración del script `threex-arpatternfile.js` originario del repositorio oficial de **AR.js** (desarrollado por Jerome Etienne y mantenido por la organización AR-js-org).
* **Asistencia Técnica:** Estructuración de la interfaz, optimización del lienzo HTML5 (Canvas) y documentación técnica elaboradas con la colaboración de **Gemini (Modelo de IA de Google)**.

---
*Herramienta distribuida bajo licencia de código abierto para fomentar la reproducibilidad en la investigación y el diseño de recursos educativos.*
