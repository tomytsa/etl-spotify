# ETL de Spotify - Canciones de Grunge

Este proyecto ETL (Extract, Transform, Load) está diseñado para extraer datos de canciones del género Grunge desde la API de Spotify, transformarlos utilizando Pandas y cargarlos en una base de datos MySQL.

## Tecnologías utilizadas

- **Python**: Lenguaje de programación principal.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **SQLAlchemy**: Herramienta para la interacción con bases de datos SQL.
- **MySQL**: Sistema de gestión de bases de datos relacional.

## Estructura del Proyecto

```
etl-spotify/
├── notebooks/          # Jupyter Notebooks para análisis y pruebas
├── src/                # Código Python (scripts separados)
├── data/               # Archivos de datos (CSV, JSON, etc.)
├── README.md           # Documentación del proyecto
├── requirements.txt    # Dependencias del proyecto
├── .gitignore          # Archivos a ignorar en Git
```

## Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tomytsa/etl-spotify.git
   cd etl-spotify
   ```

2. Crea un entorno virtual e instala las dependencias:

   ```bash
   python -m venv env
   source env/bin/activate  # En Mac/Linux
   env\Scripts\activate     # En Windows
   pip install -r requirements.txt
   ```

3. Ejecuta Jupyter Notebook para acceder a los notebooks de análisis:

   ```bash
   jupyter notebook
   ```

## Contacto

- **GitHub**: [tomytsa](https://github.com/tomytsa)
- **LinkedIn**: [Tomas Tsangoulas](www.linkedin.com/in/tomastsangoulas)

---
