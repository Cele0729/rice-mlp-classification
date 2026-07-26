# rice-mlp-classification
# 🌾 Clasificación de variedades de arroz mediante una Red Neuronal Multicapa (MLP)

## 📖 Descripción

Este proyecto implementa un modelo de **Inteligencia Artificial** basado en una **Red Neuronal Multicapa (MLP)** para clasificar automáticamente cinco variedades de arroz utilizando un conjunto de datos público de Kaggle.

El desarrollo fue realizado como parte de la asignatura **Inteligencia Artificial Avanzada** del programa de **Ingeniería de Software**.

---

# 🎯 Objetivo

Diseñar e implementar un modelo de inteligencia artificial basado en una Red Neuronal Multicapa (MLP) capaz de clasificar automáticamente cinco variedades de arroz a partir de sus características morfológicas, con el fin de apoyar la automatización del control de calidad en la industria agrícola.

---

# 📊 Dataset utilizado

**Rice MSC Dataset (Kaggle)**

Características principales:

- 75.000 muestras
- 106 variables morfológicas
- 5 variedades de arroz

Las clases utilizadas fueron:

- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

---

# 🧠 Arquitectura del modelo

La red neuronal implementada está compuesta por:

- Capa de entrada: **106 características**
- Primera capa oculta: **128 neuronas (ReLU)**
- Segunda capa oculta: **64 neuronas (ReLU)**
- Capa de salida: **5 neuronas (Softmax)**

Configuración utilizada:

- Optimizador: **Adam**
- Función de pérdida: **Sparse Categorical Crossentropy**
- Métrica: **Accuracy**

---

# ⚙️ Tecnologías utilizadas

- Python
- Google Colab
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

# 📈 Resultados obtenidos

El modelo obtuvo un excelente desempeño durante las pruebas.

| Métrica | Resultado |
|---------|-----------|
| Accuracy de entrenamiento | **99.94 %** |
| Accuracy de validación | **99.88 %** |
| Accuracy en prueba | **≈99 %** |

La matriz de confusión y el reporte de clasificación mostraron una correcta identificación de las cinco variedades de arroz.

---

# 📂 Estructura del proyecto

```text
📁 notebook/
│
└── IA_Clasificacion_Arroz_MLP.ipynb

📁 images/
│
├── accuracy.png
├── loss.png
└── confusion_matrix.png

📄 Informe.pdf

📄 README.md
```

---

# 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio.

```bash
git clone https://github.com/TU_USUARIO/rice-mlp-classification.git
```

2. Instalar las dependencias.

```bash
pip install -r requirements.txt
```

3. Abrir el notebook en Google Colab o Jupyter Notebook.

4. Ejecutar las celdas en orden.

---

# 👨‍💻 Autor

**Johan David Celemin Barragán**

Estudiante de Ingeniería de Software

Proyecto académico desarrollado para la asignatura **Inteligencia Artificial Avanzada**.
