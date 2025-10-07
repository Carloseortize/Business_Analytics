# 📈 Proyecto Showz – Optimización de Marketing Digital

Este proyecto analiza datos históricos de **visitas, pedidos y campañas publicitarias** de la empresa Showz entre enero de 2017 y diciembre de 2018. El objetivo es **entender el comportamiento de los usuarios, evaluar la efectividad de las campañas y optimizar la inversión en marketing** para maximizar la adquisición y retención de clientes.

---

## 🌐 Objetivo del proyecto

* Analizar el tráfico de usuarios y el comportamiento de compra.
* Evaluar la eficiencia de las campañas publicitarias y el Costo de Adquisición de Clientes (CAC).
* Determinar el Retorno de Inversión en Marketing (ROMI) y el Valor de Vida del Cliente (LTV).
* Proponer estrategias de marketing basadas en datos para optimizar la inversión y la retención de clientes.

---

## 🧰 Herramientas y tecnologías utilizadas

**Lenguaje y entornos:**

* Python 🐍
* Jupyter Notebook / VS Code

**Bibliotecas de análisis de datos:**

* **pandas** → Limpieza, manipulación y análisis de datasets.
* **NumPy** → Cálculos estadísticos y operaciones numéricas.
* **matplotlib** y **seaborn** → Visualización de tendencias y cohortes.
* **scipy.stats** → Pruebas estadísticas y análisis de diferencias entre grupos.

**SQL:**

* Consultas para consolidar información de campañas y ventas.

---

## 📊 Proceso de análisis

1. **Preparación de datos:**

   * Limpieza de valores ausentes y estandarización de formatos.
   * Consolidación de visitas, pedidos y gastos publicitarios.

2. **Análisis de comportamiento del usuario:**

   * Tiempo hasta la primera compra, frecuencia de compra y retención por cohorte.
   * Distribución de compras por semana, mes y año.

3. **Evaluación de marketing:**

   * Análisis de gasto por fuente de adquisición.
   * Cálculo de CAC y ROMI por fuente.
   * Identificación de fuentes más eficientes y rentables.

4. **Visualización y métricas clave:**

   * Gráficos de cohortes, evolución de visitas y compras, y tendencias de gasto.
   * Comparación de CAC y LTV por fuente para determinar retorno de inversión.

---

## 💡 Principales hallazgos

* La mayoría de los usuarios realiza la primera compra rápidamente (mediana 16 minutos), pero la retención posterior disminuye drásticamente.
* Mayor actividad durante temporada navideña, con picos de visitas y compras.
* Fuentes 9 y 10 son las más eficientes (CAC ≈ 0.14) y generan usuarios con buen retorno.
* Fuente 1 tiene CAC moderado (≈0.52) y rendimiento aceptable.
* Fuente 3 presenta el CAC más alto (3.51) y menor eficiencia, indicando baja rentabilidad.
* LTV aumenta con la antigüedad del usuario, destacando la importancia de la retención y recompra.
* Recomendación: priorizar inversión en fuentes 1, 9 y 10, evitando fuentes con alto CAC y bajo LTV.

---

## 📦 Estructura del repositorio

```
📦 Showz_Sprint9/
 ┣ 📜 data/                  # Datasets de visitas, pedidos y campañas
 ┣ 📜 notebooks/             # Análisis exploratorio y cohortes
 ┣ 📜 images/                # Gráficos de tendencias y cohortes
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

---

## ⚙️ Requisitos

* Python 3.7 o superior
* Dependencias:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

* SQL para consultas y consolidación de información de campañas.

---

## 👨‍💻 Autor

**Desarrollado por:** Carlos Ortiz
**Rol:** Data Analyst
💬 *Proyecto académico/profesional para análisis de marketing digital, optimización de CAC y mejora de retención de usuarios.*
