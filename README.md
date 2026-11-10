# Taller 2: predicción de abandono de clientes

**Estudiante:** Andrés Camilo Beltrán (ac.beltranc1@uniandes.edu.co)
**Universidad:** Universidad de los Andes, Maestría en Ingeniería de la Información (MINE)
**Materia:** Ciencia de datos

## Qué hay en la carpeta

- `taller2.ipynb`: el taller completo, con el código y los análisis de los puntos 1 al 5 y el guion de la presentación (punto 6).
- `diapositivas.pdf`: las 5 diapositivas de la presentación.
- `data/churn.csv`: copia local de los datos de clientes.
- `README.md`: archivo de descripción del directorio.

## Cómo está el notebook

Va en orden: cada punto empieza con un título y cada etapa tiene una explicación corta antes del código. Ya está ejecutado, así que se pueden ver los resultados sin ejecutarlo de nuevo.

Si se quiere ejecutar de nuevo, hay que correr las celdas de arriba hacia abajo, una tras otra, porque cada una usa variables de las anteriores.

Necesita Python con `pandas`, `numpy`, `matplotlib`, `seaborn` y `scikit-learn`, y para el punto 4 también `lime` y `shap` (`pip install lime shap`). Los datos los lee desde la dirección de la guía de la materia, así que hace falta internet; si no hay conexión, se puede cambiar esa ruta por `data/churn.csv`.

La rama principal es la main, y es donde se tiene toda la información del taller
