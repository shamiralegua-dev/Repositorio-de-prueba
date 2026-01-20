Proyecto: Website académico/Tech con dataset de titulares del Blog de Python

Objetivo: Demonstrar flujo reproducible de extracción y procesamiento de datos para comunicación digital.

Fuente: https://blog.python.org/ (consulta automatizada)

Outputs:
data/posts_python_blog.csv (titulares + URLs)
data/posts_python_blog_procesado.csv (+ longitud de título)
data/top_palabras_titulos.csv (top 20 palabras)

Cómo correr:
pip install requests beautifulsoup4 pandas
python src/scrape_python_blog.py
python src/process_posts.
