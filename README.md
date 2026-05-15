Data Scraping, Pipeline Automation & Advanced Cleansing 📊🕷️
Este repositorio reúne una colección de herramientas, scripts y pipelines de producción en Python diseñados para la extracción automatizada de datos (Web Scraping) y la transformación/limpieza profunda de archivos con estructuras complejas o inconsistentes.

🚀 Descripción General
El núcleo de este proyecto es resolver el desafío de los "datos sucios" e inaccesibles, transformando fuentes web dinámicas/estáticas y archivos crudos (unstructured data) en datasets estructurados, limpios y listos para su explotación en modelos analíticos, bases de datos SQL o tableros de Business Intelligence (Power BI).

🛠️ Tecnologías y Librerías Clave
Python 3.x como motor de procesamiento.

BeautifulSoup4 & Requests: Para la extracción de datos en páginas web estáticas y manejo de sesiones HTTP.

Selenium / Playwright: Automatización de navegadores para interactuar con sitios dinámicos (renderizado de JavaScript, clics implícitos y bypass de logins).

Pandas & NumPy: Columnas vertebrales para la manipulación, limpieza masiva, normalización y pivotaje de estructuras de datos.

Regex (Re): Expresiones regulares avanzadas para la minería de texto y validación de patrones (IDs, fechas, SKU, códigos postales).

OpenPyXL / Mocks: Procesamiento directo y optimizado de archivos Excel masivos o layouts dañados.

📁 Estructura del Repositorio y Módulos
1. Web Scraping & Extracción Automatizada (/web_scraping)
Scripts dedicados a la recolección de datos externos de manera ética y eficiente.

Scrapers Estáticos y Dinámicos: Extracción de catálogos, tablas web y precios competitivos superando barreras de carga asíncrona (AJAX/JS).

Manejo de Rate Limiting & Proxies: Implementación de retardos dinámicos y rotación básica para evitar bloqueos durante la extracción masiva.

2. Pipelines de Limpieza y Normalización (/data_cleansing)
Módulos especializados en la transformación de datos crudos (Raw Data) a datos listos para producción (Curated Data).

Tratamiento de Datos Nulos y Duplicados: Estrategias avanzadas de imputación y deduplicación basadas en lógica de negocio.

Normalización de Texto: Eliminación de caracteres especiales, acentos, estandarización de mayúsculas/minúsculas y corrección de formatos de fecha inconsistentes.

Parsing de Layouts Complejos: Conversión de reportes en formatos "humanos" (Excel con celdas combinadas, encabezados múltiples o subtotales intercalados) en tablas relacionales limpias.

3. Validadores y Control de Calidad (/data_validation)
Scripts de auditoría para asegurar la integridad de los datos antes de su ingesta en sistemas core.

Reglas de Negocio Automatizadas: Validación de tipos de datos, rangos permitidos y consistencia lógica entre columnas.

Generación de Logs de Errores: Reportes automatizados que identifican filas o registros corruptos para su posterior revisión.

📈 Casos de Uso e Impacto
Automatización de Reportes: Eliminación de horas hombre dedicadas a descargar, copiar y pegar información manualmente de portales web o archivos locales.

Estandarización de Catálogos: Limpieza y homologación de bases de datos de proveedores, materiales o clientes para evitar duplicidad operativa.

Migración de Datos Confiable: Preparación y empaquetado de datos históricos limpios para alimentar bases de datos relacionales (SQL) sin errores de llave o restricción.
🧑‍💻 Autor
Irving Gerardo Campos Gómez - Head of Technological Evolution / Logistics & IT Specialist
