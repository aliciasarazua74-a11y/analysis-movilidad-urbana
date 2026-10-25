## Analysis-movilidad-urbana

Este repositorio contiene el análisis realizado del caso movilidad-urbana. El objetivo del estudio es identificar en qué ciudades invertir en infraestructura de transporte para aumentar la productividad y el bienestar de la población.

El dataset tomtom_traffic.csv contiene datos sobre congestión vehicular y condiciones de tráfico en ciudades del mundo. oecd_city_economy.csv contiene indicadores económicos y ambientales por ciudad, recopilados por la OECD (Organización para la Cooperación y el Desarrollo Económico).

📂 Contenido del repositorio
mobility_economy.ipynb → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.
▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

Open In Colab

O:

Abre el archivo .ipynb en GitHub
Haz clic en Open in Colab
📘 Cómo reproducir el análisis
mobility_economy.ipynb
Ejecuta las celdas en orden
El notebook carga automáticamente el dataset desde /data/ o desde un enlace público (según corresponda)

🧠 Objetivo del análisis
Crear un dataset único y limpio a partir de dos fuentes diferentes.
Aplicar limpieza, estandarización y validación de tipos de datos.
Filtrar y enfocar el análisis en el año 2024.
Calcular indicadores agregados (por ciudad–año).
Realizar análisis exploratorios y visuales.

📊 Hallazgos
La relación entre movilidad urbana y productividad económica no es claramente lineal. Algunas ciudades con un PIB per cápita alto presentan niveles elevados de congestión, como Ciudad de México (25,000) , lo que indica que una economía fuerte no necesariamente implica una movilidad eficiente. Por otro lado, algunas ciudades con menor PIB per cápita también presentan congestión considerable. Esto sugiere que factores como el tamaño de la población, infraestructura vial y eficiencia del transporte pueden influir en la movilidad además del nivel económico.

💡 Recomendaciones
Ciudad prioritaria: Bogotá, priorizar estudios de inversión en transporte público, infraestructura vial y reducción de tiempos de traslado. 
Ciudad prioritaria: Lima, valuar corredores con mayor congestión y su impacto sobre actividad económica. 
Ciudad prioritaria: Buenos Aires, analizar por qué una alta congestión coexiste con un PIB per cápita relativamente elevado.
