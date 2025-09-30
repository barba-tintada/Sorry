# Will It Rain On My Parade? 🌦️

**2025 NASA Space Apps Challenge – Intermediate Level**

Bienvenidos al repositorio oficial de nuestro proyecto para el NASA Space Apps Challenge 2025. Nuestro objetivo es desarrollar una aplicación que permita a los usuarios conocer la probabilidad de condiciones climáticas extremas o incómodas para una ubicación y fecha específicas, basada en datos históricos de observación de la Tierra proporcionados por la NASA. Con otras funcionalidades curiosas que complementan esta aplicación.

---

## 🔹 Descripción del Proyecto

Si estás planeando un evento al aire libre —como una caminata, un paseo, pesca, o un picnic— saber las probabilidades de mal clima puede ser crucial. Nuestro proyecto utiliza datos históricos de la NASA para informar a los usuarios sobre la probabilidad de condiciones como:

* Muy caluroso
* Muy frío
* Muy ventoso
* Muy húmedo/lluvioso
* Generalmente incómodo

La aplicación no es un pronóstico del clima, sino una herramienta basada en datos históricos que permite a los usuarios tomar decisiones más informadas para su planificación.

---

## 🔹 Objetivos

* Construir un **dashboard interactivo y personalizado** donde los usuarios puedan seleccionar:

  * Ubicación (por nombre, pin en mapa o límites dibujados)
  * Día del año o rango de fechas
* Mostrar la probabilidad de condiciones climáticas extremas usando gráficos y mapas.
* Proveer opciones de **descarga de datos** en formatos CSV o JSON, con metadatos y enlaces a las fuentes de la NASA.
* Presentar la información de manera accesible y visual, incluyendo:

  * Curvas de probabilidad
  * Series temporales de datos
  * Mapas interactivos

---

## 🔹 Datos y Recursos

* Datos históricos de observación de la Tierra de NASA: lluvia, velocidad del viento, temperatura, nieve, polvo, cobertura de nubes, índices de extremas temperaturas, entre otros.
* Modelos de NASA para calcular probabilidades de condiciones climáticas extremas.
* Herramientas de visualización y análisis de datos para representar resultados de manera clara y comprensible.

**Enlaces de interés:**

* [NASA Earth Observation Data](https://earthdata.nasa.gov/)
* [Recursos del Space Apps Challenge](https://2025.spaceappschallenge.org/)

---

## 🔹 Funcionalidades del Proyecto

* Selección de ubicación por:

  * Nombre de ciudad
  * Pin en mapa interactivo
  * Dibujo de límites en mapa
* Visualización de probabilidades de eventos climáticos:

  * Gráficos de barras o líneas
  * Mapas de calor por ubicación
  * Textos explicativos simples
* Descarga de datos relevantes según la consulta del usuario:

  * Formatos CSV y JSON
  * Incluye unidades y fuentes
* Dashboard personalizable según preferencias del usuario

---

## 🔹 Tecnologías

* **Frontend:** React, Leaflet.js (mapas), Chart.js / D3.js (visualización)
* **Backend:** Python, Flask / FastAPI (API de datos y procesamiento)
* **Datos:** NASA Earth Observation datasets, APIs de NASA

---

## 🔹 Consideraciones

* Elegir cuidadosamente las variables mostradas para no sobrecargar al usuario.
* Priorizar datos relevantes para actividades al aire libre.
* Garantizar que la información se presente de manera visual e intuitiva.
* Posibilidad de expandir la app a nuevas variables o regiones en el futuro.

---

## 🔹 Equipo

* Marcos Mesa
* Raúl Martín
* Cristian Gil
* Rubén Morales

---

## 🔹 Estado del Proyecto

* [ ] Recolección de datos
* [ ] Procesamiento y análisis de datos
* [ ] Desarrollo del backend
* [ ] Desarrollo del frontend
* [ ] Integración y pruebas
* [ ] Documentación y despliegue

---

## 🔹 Licencia

Este proyecto está bajo licencia MIT.


