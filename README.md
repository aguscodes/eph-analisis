# Proyecto 2: ¿Qué variables influyen en los ingresos de una persona en relación de dependencia?

## 📌 Descripción
Este proyecto que hice con mis compañeros de la materia Introducción al aprendizaje automático investigamos qué características del trabajo y sociales afectan los ingresos en relación de dependencia en base a datos de la Encuesta Permanente de Hogares.

## 🔍 Objetivo
Identificar qué características del empleo y de la persona tienen mayor impacto en los ingresos, en el primer cuatrimestre del 2023. Si existe alguna tendencia o algúnfactor que aumente o disminuya el ingreso.

## 📊 Dataset
- **Fuente:** Encuesta Permanente de Hogares (EPH)
- **Variables clave:**
     - **Target: Ingreso empleo principal**
     - **Categóricas:** región, aglomerado, estado civil, obra social, lugar de nacimiento, intensidad laboral, tipo de empleo, turno, metodo de pago, sección laboral.
     - **Encuestas si/no:** sabe leer y escribir, tiene vacaciones pagas, tiene aguinaldo, tiene dás por enfermedad, tiene obra social, tiene descuento jubilatorio, aporta a su jubilación.
     - **Numéricas:** Sexo, Edad y Nivel educativo

## 🛠️ Metodología
1. **Limpieza de datos:** Eliminación de valores inconsistentes, estandarización de variables, transformación logarítmica.
2. **Análisis exploratorio:** Visualización de distribuciones salariales y correlaciones entre variables,  en cuanto a si sabía leer y escribir y su región.
3. **Modelos predictivos:** Implementación de regresión linealcon 3 variables. Otra con Lasso y Lasso CV pero sin región ni aglomerado y finalmente con región.

## 🔎 Principales hallazgos
- El aglomerado no pudo ser incluido debido a que daba valores de coeficientes sin sentido.
- Se identificaron los perfiles de trabajadores con mejores y peores salarios.
- Variables como la región, la intensidad laboral, el sexo, el metodo de pago y otros tienen un impacto significativo en los ingresos.
- El modelo con Lasso CV permitió mejorar la precisión en la predicción salarial.

## 🛠️ Tecnologías utilizadas
- Python (pandas, seaborn, scikit-learn)
- Jupyter Notebook
- Machine Learning (Lasso, Lasso CV)

## 📂 Archivos
- `analisis eph.ipynb`: Código del análisis.
- `eph_datos.csv`: Dataset utilizado.
- `EPH- Project ML.pdf`: Resumen visual del análisis (opcional).


- Si el dataset no es público, puedes compartir solo un ejemplo o explicar cómo obtenerlo.

¡Listo! Ahora puedes completar y personalizar los README según lo necesites. 🚀
