Para el uso correcto del código en necesario seguir el siguiente procedimiento

- Instalar extensión de jupyter en VScode

- El dataset de la pregunta 2 debe ser guardado en la carpeta data con el nombre de "HumanRecognition", no se pudo subir a github por el tamaño del dataset. Además se utilizó el "UCI HAR Dataset" si se quiere utilizar el 2 se puede cambiar dentro del código en la sección 1 de carga del dataset.

- Crear el entorno para desarrollo y pruebas:
python3 -m venv .venv

- Activar el entorno:
source .venv/bin/activate

- Actualizar python en el terminal del entorno para utilizacion de librerias bayesianas:
python -m pip install --upgrade pip
pip install pgmpy==0.1.25

Las herramientas generativa a utilizar fue Claude con el propósito de generar código y evitar errores de una programación incorrecta y se utilizó SOLO para corregir redacción. En la sección de análisis no se utilizó ninguna herramienta.