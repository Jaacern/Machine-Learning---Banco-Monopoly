# 📊 Análisis Predictivo de Morosidad de Clientes Bancarios

Este repositorio contiene un estudio de caso orientado a la aplicación de técnicas de minería de datos y aprendizaje automático para predecir el comportamiento financiero de los clientes de una entidad bancaria ficticia. El objetivo principal es construir modelos predictivos que permitan estimar la probabilidad de morosidad y el posible monto de deuda futura.

---

## 📘 Descripción del Proyecto

La institución financiera ficticia **Banco Dormaammu** busca optimizar sus estrategias de captación y retención de clientes mediante el análisis del comportamiento financiero. Se dispone de un conjunto de datos simulados, proporcionado por el banco ficticio chileno **Monopoly**, que incluye información transaccional y financiera de clientes durante un periodo de 12 meses.

El desarrollo del proyecto sigue la metodología **CRISP-DM** (Cross Industry Standard Process for Data Mining), abarcando desde la comprensión del negocio y los datos, hasta la construcción de modelos predictivos.

---

## 🎯 Objetivos

- **Clasificación binaria**: Predecir si un cliente será moroso (`1`) o no moroso (`0`).
- **Regresión**: Estimar la probabilidad de incumplimiento o el monto esperado de deuda.
- **Perfilamiento de clientes**: Identificar patrones para segmentación y toma de decisiones estratégicas.

---

## 🧰 Herramientas y Tecnologías

- **Lenguaje de programación**: Python 3.8+
- **Análisis y manipulación de datos**:
  - `pandas`
  - `numpy`
- **Visualización de datos**:
  - `matplotlib`
  - `folium` (visualización geográfica)
- **Análisis exploratorio automatizado**:
  - `ydata-profiling` (antes `pandas-profiling`)
- **Modelado predictivo** (en desarrollo):
  - `scikit-learn`
  - `xgboost` *(previsto)*
  - `lightgbm` *(previsto)*

---

## 📁 Estructura del Proyecto

```
proyecto-morosidad-clientes/
│
├── Copia_de_E1_MLY0100_Base.ipynb  # Notebook principal
├── data/                           # Carpeta para datasets (no incluidos)
├── output/                         # Resultados, gráficos y modelos generados
├── requirements.txt                # Dependencias del proyecto
└── README.md                       # Documentación general
```

---

## 📝 Instrucciones de Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jaacern/Machine-Learning---Banco-Monopoly.git
   cd Machine-Learning---Banco-Monopoly
   ```

2. Instala las dependencias:
   ```bash
   #pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter notebook Copia_de_E1_MLY0100_Base.ipynb
   ```

---

## 🔐 Consideraciones Éticas y de Privacidad

Todos los datos utilizados son **completamente ficticios** y fueron generados con fines educativos. No representan información real ni contienen datos personales o sensibles.

---

## 👨‍💻 Autor

**[ ]**  
 Ciencia de Datos / Analítica Predictiva  


---

## 📄 Licencia

Este proyecto se encuentra bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más información.
