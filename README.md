 # Agente de Investigación de Audiencias IA - Televisa Univision

## Descripción del Proyecto

Este proyecto es una solución integral de inteligencia artificial diseñada para el área de Investigación de Inteligencia de Audiencias de Televisa Univision. Su objetivo principal es consolidar, procesar y analizar grandes volúmenes de información cualitativa y cuantitativa de investigaciones, que se encuentran en múltiples formatos como videos, PDFs, audios y bases de datos.

El proyecto permite:
- Responder preguntas en lenguaje natural sobre los contenidos de investigación.
- Desarrollar análisis predictivos para generar escenarios posibles.
- Identificar patrones y tendencias en los datos.
- Proporcionar insights a través de informes automatizados.

La implementación de este agente de IA busca reducir significativamente los tiempos de investigación, optimizar recursos y coadyuvar a una toma de decisiones más rápida y precisa por parte de los equipos de producción, escritores y analistas.


<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/e0774b6e-b55f-46ab-b6bd-3d5682d7c866" />



## Arquitectura de la Solución

La solución se construye sobre la plataforma de IA y datos de IBM watsonx, utilizando una arquitectura modular que conecta sus componentes principales para un flujo de trabajo optimizado.

- **watsonx.data**: Actúa como el lakehouse empresarial para la consolidación de todas las fuentes de datos heterogéneas.
- **watsonx Discovery**: Se encarga del procesamiento y enriquecimiento de documentos no estructurados (textos, transcripciones), creando una base de conocimiento vectorial para búsquedas rápidas y precisas.
- **watsonx.ai**: Es el motor de inteligencia artificial que utiliza modelos fundacionales para la generación de resúmenes, clasificación de contenidos y, potencialmente, la afinación con la terminología de contenidos de Televisa. Además, aquí se implementarán los modelos de Machine Learning para el análisis predictivo.
- **Portal Web a Medida**: Un desarrollo web personalizado servirá como la interfaz principal de usuario, permitiendo la interacción conversacional y la visualización de dashboards, metadatos y análisis en tiempo real.
- **watsonx.governance**: Asegura la transparencia, auditabilidad y gestión de riesgos de la IA, monitoreando la solución a lo largo de su ciclo de vida.

## Requisitos Técnicos

Para ejecutar y desarrollar el proyecto, se necesitan los siguientes requisitos:

- **Node.js**: Entorno de ejecución para JavaScript del lado del servidor.
- **npm (Node Package Manager)**: Gestor de paquetes para instalar dependencias.
- **Git**: Sistema de control de versiones.
- **Acceso a la plataforma IBM watsonx**: Se requiere una cuenta con acceso a los servicios de watsonx.ai, watsonx Discovery y watsonx.data.
- **Claves de API**: Para la conexión a los servicios de watsonx, las claves de API se almacenarán en el archivo `.env`.

## Estructura del Proyecto

La estructura de carpetas sigue una convención moderna y modular para facilitar el desarrollo y la escalabilidad.


## Guía de Instalación y Uso

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu_usuario/research-agent-televisa.git](https://github.com/tu_usuario/research-agent-televisa.git)
    cd research-agent-televisa
    ```

2.  **Instalar dependencias:**
    ```bash
    npm install
    ```

3.  **Configurar variables de entorno:**
    Crea un archivo `.env` en la raíz del proyecto y añade tus credenciales.
    ```
    WATSONX_API_KEY=tu_clave_de_api
    WATSONX_DISCOVERY_URL=tu_url_de_discovery
    ```

4.  **Ejecutar la aplicación en modo desarrollo:**
    ```bash
    npm start
    ```

5.  **Abrir en el navegador:**
    La aplicación estará disponible en `http://localhost:3000`.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarnos.

- **Tu Nombre** - [correo@ejemplo.com](mailto:correo@ejemplo.com)
