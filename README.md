# pandas-ES-CSV.
📊 Clase 1: Introducción a Pandas con Archivos CSV
Curso: Ciencia de Datos con Python – Alura
Plataforma: Google Colab 🚀

🧠 ¿Qué aprenderás en esta clase?
En esta primera clase te sumergirás en el mundo de los datos estructurados utilizando la biblioteca Pandas de Python. Nos enfocaremos en trabajar con archivos CSV (Comma-Separated Values), un formato muy común para almacenar datos tabulares.

📌 Contenidos de la clase
🔍 ¿Qué es un archivo CSV?

Comprenderás qué es un archivo CSV y por qué es tan utilizado en análisis de datos.

Verás ejemplos de archivos separados por comas (,) y por punto y coma (;).

📥 Leer archivos CSV con Pandas

Usarás pd.read_csv() para leer archivos en diferentes formatos.

Cargarás archivos separados por coma y por punto y coma.

Leerás solo ciertas filas (nrows) y columnas específicas (usecols) para optimizar la carga de datos.

✂️ Lectura parcial de archivos

Aprenderás a seleccionar solo una porción del archivo CSV según lo que necesites analizar.

Ideal para archivos grandes o exploración rápida de datos.

📤 Escribir archivos CSV

Guardarás tus DataFrames en un archivo CSV usando to_csv().

Aprenderás a controlar el formato de salida (sin índice, separadores, codificación, etc.).

🛠️ Tecnologías utilizadas
🐍 Python 3

🐼 Pandas

📓 Google Colab

▶️ ¿Cómo ejecutar esta clase?
Abre el siguiente enlace de Colab: (agrega aquí el link de tu notebook)

Asegúrate de tener archivos CSV cargados en el entorno o usa los de ejemplo.

Ejecuta cada celda y ¡a aprender! 💡

💾 Ejemplo de uso de read_csv()


import pandas as pd

# Leer un archivo separado por comas
df = pd.read_csv('archivo_comas.csv')

# Leer un archivo separado por punto y coma
df2 = pd.read_csv('archivo_puntocoma.csv', sep=';')

# Leer solo las primeras 5 filas y columnas específicas
df3 = pd.read_csv('archivo.csv', nrows=5, usecols=['Nombre', 'Edad'])



✨ Resultado esperado
Al finalizar esta clase serás capaz de:

✅ Identificar y trabajar con archivos CSV.
✅ Leer archivos completos o parcialmente.
✅ Escribir tus propios archivos CSV desde Pandas.
✅ Prepararte para análisis de datos más avanzados.

📚 Créditos
🎓 Curso impartido por Alura
👨‍💻 Elaborado por Carlos Alberto Villa Tobon
