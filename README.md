# Visor GIS para trabajo de campo

Herramienta web ligera para levantamiento de información geoespacial en campo. Diseñada para profesionales forestales, ambientales o cualquier técnico que necesite interactuar con datos espaciales fuera de la oficina.

## ¿Por qué esta herramienta?

El trabajo de campo con información geoespacial suele enfrentarse a aplicaciones rígidas, interfaces poco intuitivas y dificultades para consultar y registrar datos sobre el terreno. Este visor nace de la necesidad de tener una herramienta ágil, transparente y sin dependencias complejas.

## Funcionalidades

| Módulo | Qué hace |
|--------|----------|
| 📍 GPS | Seguimiento en tiempo real. Centra automáticamente al iniciar. |
| 📐 Dibujo | Polígonos a mano alzada con cálculo de área geodésica (m² y ha). |
| 🎯 Tracker | Graba tu recorrido y lo cierra como polígono al finalizar. |
| 📂 Importación | Carga archivos GeoJSON existentes (polígonos). Los añade al mapa manteniendo sus propiedades. |
| 📌 Puntos de campo | Registro con coordenadas, timestamp y observaciones. |
| 🗺️ Capas base | Ortofoto PNOA y callejero OpenStreetMap (intercambiables). |
| 💾 Exportación | GeoJSON listo para QGIS u otro SIG. |
| 🧭 Extras | Brújula orientable, barra de escala dinámica, interfaz responsive. |

## Tecnologías

- [OpenLayers](https://openlayers.org/) v10.2.1
- JavaScript vanilla (sin frameworks)
- Geolocation API
- PNOA WMS / OpenStreetMap tiles

## Cómo usarlo

1. Abre el enlace del visor
2. Permite el acceso a la ubicación cuando el navegador lo solicite
3. Comienza a usar las herramientas

> ⚠️ Las capas base requieren conexión a internet. El resto funciona sin backend ni instalación.

## Estado del proyecto

Prototipo funcional, utilizado en campañas de campo reales. Dista de ser una aplicación completa, pero cumple con lo que necesitaba sobre el terreno. Publicado en abierto por si a alguien le resulta útil o inspiración para proyectos mayores.

## Autor

Ander — Ingeniero Técnico Forestal, especializado en GIS y teledetección.

## Licencia

MIT. Usa, modifica, mejora.
