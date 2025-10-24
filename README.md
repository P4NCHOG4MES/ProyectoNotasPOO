📄 README.md
# Proyecto Registro de Notas

Este proyecto permite registrar y visualizar las notas de un estudiante utilizando HTML, Python y CSS.  
Incluye un formulario para ingresar notas, un archivo JSON para almacenar los datos y un script en Python para generar un resultado visual con gráfico y promedio.

Archivos del proyecto
- `registro_notas.html` → Formulario web para ingresar el nombre del estudiante y las notas de 5 asignaturas.
- `notas.py` → Script en Python que lee el archivo JSON, calcula el promedio, genera una gráfica de barras y crea un archivo HTML con los resultados.
- `styles.css` → Estilo oscuro y moderno para el formulario y los resultados.
- `resultado.html` → Archivo generado por `notas.py` mostrando las notas, promedio y gráfica.
- `grafica.png` → Gráfica de notas generada por Python.
- `notas.json` → Archivo JSON generado desde el formulario HTML.

Diseño y características
- Tema oscuro con estilo moderno y llamativo.
- Entrada de datos sencilla e intuitiva.
- Visualización clara del promedio y de cada asignatura.
- Gráfica de barras para representar las notas.

Cómo usar el proyecto

1. Abre `registro_notas.html` en tu navegador.
2. Ingresa el nombre del estudiante y las notas de las 5 asignaturas.
3. Presiona "Guardar en JSON" para generar `notas.json`.
4. Ejecuta el script `notas.py`:

Se generarán dos archivos:
  resultado.html → Visualiza las notas y el promedio.
  grafica.png → Gráfica de barras de las notas.
Abre resultado.html en tu navegador para ver el resultado final.

Requisitos

  Python
  
Librerías:

pandas, matplotlib

Navegador moderno compatible con la API showSaveFilePicker() (Chrome, Edge o Brave recomendados).

🔗 Repositorio

https://github.com/P4NCHOG4MES/ProyectoNotasPOO
