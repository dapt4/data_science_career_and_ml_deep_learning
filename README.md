# Ciencia de Datos: carrera, Machine Learning y Deep Learning

Repositorio de aprendizaje con notebooks de Jupyter sobre fundamentos de Machine Learning y álgebra lineal aplicada, todos en Python.

## 📁 Estructura

| Carpeta | Contenido |
|---|---|
| [`1_fundamentos_ml/`](1_fundamentos_ml/) | Flujo completo de ML con el caso práctico del equipo **"Cebollitas"**: preparación, exploración, escalado, ingeniería y selección de características, regresión lineal, evaluación, clustering K-Means, PCA, pipelines, redes neuronales y una introducción a NLP. |
| [`algebra_Lineal_Aplicada_a_Machine_Learning1/`](algebra_Lineal_Aplicada_a_Machine_Learning1/) | Primeros pasos con vectores y cómo graficarlos. |
| [`2_curso_de_algebra_lineal-fundamentos_y_aplicaciones/`](2_curso_de_algebra_lineal-fundamentos_y_aplicaciones/) | Fundamentos de álgebra lineal (en curso). |
| [`3_curso_de_algebra_Lineal_Aplicada_para_ML/`](3_curso_de_algebra_Lineal_Aplicada_para_ML/) | Autovalores y autovectores, su cálculo con NumPy y descomposición de matrices. |

### Datasets incluidos (`1_fundamentos_ml/`)

- `partidos_cebollitas.csv`: resultados y estadísticas de los partidos.
- `jugadores_cebollitas.csv`: métricas de los jugadores (para clustering y PCA).
- `comentarios_deportivos.csv`: textos para los ejercicios de NLP.

## 🛠️ Tecnologías

Python, Jupyter, NumPy, pandas, Matplotlib, scikit-learn e ipywidgets.

## 🚀 Puesta en marcha

Cada carpeta es un proyecto independiente gestionado con **Poetry** (`pyproject.toml` y `poetry.lock`).

```bash
cd 1_fundamentos_ml
poetry install
poetry run jupyter lab
```

O, si prefieres `pip` y un entorno virtual (en `1_fundamentos_ml` hay un `requirements.txt`):

```bash
cd 1_fundamentos_ml
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## 📚 Orden recomendado

1. `1_fundamentos_ml`: los notebooks están numerados del `02` al `22`.
2. `algebra_Lineal_Aplicada_a_Machine_Learning1`
3. `2_curso_de_algebra_lineal-fundamentos_y_aplicaciones`
4. `3_curso_de_algebra_Lineal_Aplicada_para_ML`
