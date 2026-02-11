# Taller 3

Este proyecto analiza y relaciona datos de **sensores agrícolas** y **telemetría energética** para extraer hallazgos operativos y responder preguntas de negocio con evidencia cuantitativa.

En el componente **Agro**, se exploran patrones geoespaciales de los sensores (coordenadas GPS), la **biomasa** usando **NDVI**, y variables ambientales como **humedad** y **viento**, incluyendo escenarios con datos ruidosos y su limpieza para mejorar interpretabilidad.  

En el componente **Energía**, se estudian series de tiempo de variables como **demanda**, **precio spot**, **temperatura**, **generación eólica** y **costo del gas**, evaluando estacionariedad, comportamiento tipo drift/random walk, y analizando el contenido espectral (FFT) para identificar ruido inyectado.

Finalmente, el proyecto construye un **grafo dirigido de telemetría** a partir de relaciones `Source_Node → Target_Node` para medir centralidades, identificar nodos críticos y conectar la estructura de red con la estabilidad operativa y el modelado predictivo (p. ej., ARIMAX con variables exógenas).
