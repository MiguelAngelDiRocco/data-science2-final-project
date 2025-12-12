# Predicción de PM2.5 mediante Machine Learning
## Análisis Global de Factores Meteorológicos y Socioeconómicos

**Carrera:** Data Science II  
**Institución:** Coderhouse  
**Alumno:** Miguel Ángel Di Rocco  
**Entrega:** Proyecto Final 
**Fecha de Entrega:** 12/12/2025

---

## 🔗 Enlaces al Proyecto

📓 **Notebook Principal:** [Google Colab](https://colab.research.google.com/drive/1fyTevP6IlGcZjw8F28g9cc_LqmaCPa_s?usp=sharing) 
📊 **Dataset Original:** [Global Weather Repository - Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)
   **Presentación:** [Presentación](https://www.canva.com/design/DAG2XdBF6fg/NXjpnawMmvDvBA1SqUuxDQ/edit?utm_content=DAG2XdBF6fg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
---

## 📋 Descripción General

Este proyecto tiene como objetivo **predecir concentraciones de material particulado fino (PM2.5)** a nivel global, analizando la influencia de factores meteorológicos, temporales y socioeconómicos.

### **Contexto del Problema**

La contaminación por PM2.5 es uno de los principales riesgos para la salud pública según la OMS, causando más de **4 millones de muertes prematuras anuales**. Comprender los factores que influyen en su concentración es crítico para:
- Sistemas de alerta temprana en salud pública
- Políticas de control de emisiones
- Planificación urbana sostenible

---

## 📊 Dataset
  
**Enriquecimiento externo:** API RestCountries (población y densidad)  
**Período de datos:** Mayo 2024 - Abril 2025 (12 meses)  
**Cobertura geográfica:** 190 países

### **Dimensiones del Dataset Final**
- **Registros:** 78,238 (después de filtrado de outliers)
- **Variables:** 13 (1 target + 12 features)
- **Variable objetivo:** `pm25_log` - Concentración de PM2.5 transformada logarítmicamente

### **Variables Predictivas Clave**
- **Meteorológicas:** Velocidad del viento, temperatura, humedad, nubosidad, UV, precipitación
- **Temporales:** Mes, hora del día (estacionalidad y patrones diurnos)
- **Socioeconómicas:** Densidad poblacional por país
- **Binarias derivadas:** Indicadores de lluvia y viento fuerte (threshold effects)

---

**Entorno de desarrollo:**
- Google Colab
  
---

## 📫 Contacto

**Miguel Ángel Di Rocco**  
📧 Email: [migueldirocco.ds@gmail.com](mailto:migueldirocco.ds@gmail.com)  
🔗 LinkedIn: [Linkedin](https://www.linkedin.com/in/miguelangeldirocco/)  
🐙 GitHub: [MiguelAngelDiRocco](https://github.com/MiguelAngelDiRocco)

---

## ✅ Estado del Proyecto

🚧 **En desarrollo**  
📅 **Entrega 1:** ✔️ Completada (EDA + Feature Engineering)  
📅 **Entrega 2:** ✔️ Completada (Modelado + Validación) 

---

## 📜 Licencia

Este proyecto es de uso académico para el curso de Data Science II de Coderhouse.

---

## 🙏 Agradecimientos

- **Coderhouse** por la formación en Data Science
- **RestCountries API** por los datos poblacionales
- Comunidad de **Kaggle** por compartir el dataset original

---

⭐ Si este proyecto te resultó útil, ¡considera darle una estrella en GitHub!
