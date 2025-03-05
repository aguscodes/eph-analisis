# Proyecto 2: ¿Qué variables influyen en los ingresos de una persona en relación de dependencia?

## 📌 Descripción
Este proyecto investiga qué características del trabajo y sociales afectan los ingresos en relación de dependencia en base a datos de la Encuesta Permanente de Hogares.

## 🔍 Objetivo
Identificar qué características del empleo y de la persona tienen mayor impacto en los ingresos, en el primer cuatrimestre del 2023.

## 📊 Dataset
- **Fuente:** Encuesta Permanente de Hogares (EPH)
- **Variables clave:** sexo, nivel educativo, región, cobra aguinaldo?, tipo de empleo, .

## 🛠️ Metodología
1. **Limpieza de datos:** Eliminación de valores inconsistentes y estandarización de variables.
2. **Análisis exploratorio:** Visualización de distribuciones salariales y correlaciones entre variables.
3. **Modelos predictivos:** Implementación de regresión lineal con Lasso y Lasso CV para predecir ingresos.

## 🔎 Principales hallazgos
- Se identificaron los perfiles de trabajadores con mejores y peores salarios.
- Variables como educación y región tienen un impacto significativo en los ingresos.
- El modelo con Lasso CV permitió mejorar la precisión en la predicción salarial.

## 🛠️ Tecnologías utilizadas
- Python (pandas, seaborn, scikit-learn)
- Jupyter Notebook
- Machine Learning (Lasso, Lasso CV)

## 📂 Archivos
- `ingresos_trabajadores.ipynb`: Código del análisis.
- `eph_datos.csv`: Dataset utilizado (si es público, incluir enlace).
- `presentación.pdf`: Resumen visual del análisis (opcional).

## 🚀 Cómo usar este repositorio
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/ingresos-trabajadores.git
   ```
2. Abrir el Jupyter Notebook y ejecutar las celdas.

---

📌 **Notas:**
- Si hay gráficos relevantes, se pueden agregar imágenes en el README usando:
  ```markdown
  ![Descripción del gráfico](ruta/del/archivo.png)
  ```
- Si el dataset no es público, puedes compartir solo un ejemplo o explicar cómo obtenerlo.

¡Listo! Ahora puedes completar y personalizar los README según lo necesites. 🚀
