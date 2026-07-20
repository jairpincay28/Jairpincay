# Plataforma de Gestión y Monitoreo Ambiental - OpenAQ Dashboard

Este proyecto consiste en una interfaz de usuario (Dashboard) para una plataforma de gestión ambiental que simula el monitoreo de dispositivos IoT (como placas ESP32 con sensores DHT22 en Wokwi). 

El diseño está desarrollado bajo un enfoque **100% estático**, priorizando la ligereza y la velocidad de carga al prescindir por completo de código imperativo o dependencias complejas de ejecución.

## Características del Proyecto

*   **Zero JavaScript:** Los gráficos e indicadores se renderizan de manera puramente declarativa utilizando HTML, CSS moderno y elementos gráficos vectoriales (SVG).
*   **Sin Frameworks:** Construido exclusivamente con tecnologías web nativas (HTML5 y CSS3), garantizando compatibilidad absoluta e inmediata con cualquier navegador web.
*   **Layout Profesional:** Estructura modular dividida en una barra lateral de navegación (`sidebar`), un panel de métricas clave, visualización de mapas, tablas de datos estructuradas y paneles de tendencias históricas.
*   **Visualización de Datos Nativa:** El histórico de humedad utiliza curvas SVG nativas, mientras que las barras de temperatura y calidad del aire se maquetan mediante Flexbox y CSS clásico.

## Estructura del Proyecto

El proyecto está organizado de la forma más simple posible para facilitar su mantenimiento:

```text
├── index.html          # Estructura de la página y contenido de los paneles
├── styles.css          # Estilos del dashboard, tipografías y maquetación visual
├── README.md           # Documentación del proyecto