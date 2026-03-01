# Proyecto Minería de Textos: Creador de Equipo Pokémon Eléctrico Óptimo 

Este proyecto de Google Colab es una herramienta integral para entrenadores Pokémon que buscan formar el equipo eléctrico más estratégico. Combina técnicas de web scraping, procesamiento de lenguaje natural (NLP) y aprendizaje automático para analizar un vasto conjunto de datos de Pokémon y movimientos, y así sugerir equipos y conjuntos de movimientos optimizados.

##  Características Destacadas

-   **Extracción de Datos Avanzada**: Recolecta automáticamente estadísticas de Pokémon (PS, Ataque, Defensa, At. Especial) y descripciones de movimientos de fuentes confiables como [Wikidex](https://www.wikidex.net/) y [PokeAPI](https://pokeapi.co/).
-   **Clasificación de Movimientos con IA**: Utiliza un modelo de Machine Learning entrenado con NLP (`spaCy` y `RandomForestClassifier`) para clasificar de forma inteligente los movimientos en ofensivos o defensivos basándose en su descripción.
-   **Selección de Equipos Estratégicos**:
    -   Identifica los Pokémon eléctricos con mayor **potencial defensivo**.
    -   Determina los Pokémon eléctricos con mayor **poder ofensivo** (calculado a partir de su Ataque Especial y la potencia de sus movimientos eléctricos).
    -   Construye un **equipo final sinérgico** de hasta 6 Pokémon, priorizando la diversidad de tipos para una cobertura estratégica en batalla.
-   **Optimización de Conjuntos de Movimientos**: Asigna automáticamente los 3 movimientos ofensivos más potentes y 1 movimiento defensivo clave para cada Pokémon del equipo final.
-   **Visualización Interactiva y Detallada**: Presenta el equipo seleccionado con sus sprites animados, estadísticas clave y un desglose claro de sus movimientos recomendados, todo ello en una interfaz HTML/CSS atractiva.

##  Tecnologías Utilizadas

-   **Python**: Lenguaje de programación principal.
-   **Pandas**: Manipulación y análisis de datos.
-   **BeautifulSoup & Requests**: Web scraping para extraer información de sitios web.
-   **SpaCy**: Biblioteca de procesamiento de lenguaje natural para tokenización y lematización.
-   **Scikit-learn**: Herramientas para el entrenamiento y evaluación del modelo de clasificación (RandomForestClassifier).
-   **Matplotlib & Seaborn**: Generación de gráficos para visualización de datos.
-   **HTML/CSS**: Para la presentación interactiva y visual del equipo final.

##  Cómo Usar

1.  **Abrir en Google Colab**: Haz clic en el siguiente enlace para abrir el notebook directamente en Google Colab:
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JUnQh2yLxX1JvTmkSwQd-atp7B30kAM3#scrollTo=7FomYg9V0vEj)
2.  **Ejecutar Todas las Celdas**: Una vez abierto, simplemente ve a `Entorno de ejecución` > `Ejecutar todas las` (o presiona `Ctrl+F9`).
    -   El notebook se encargará automáticamente de instalar las dependencias necesarias, realizar el scraping de datos, entrenar el modelo de NLP y presentar los equipos óptimos.
3.  **Explorar el Resultado**: Al finalizar la ejecución, verás las gráficas de los equipos defensivos y ofensivos, así como la visualización interactiva del equipo final con sus movimientos recomendados.

¡Prepárate para dominar la liga Pokémon con tu equipo eléctrico optimizado!
