# Tarea 3 – Visualización y Storytelling con Datos
### Brecha Digital Global: Evolución, Desigualdad y Futuro del Acceso a Internet (1990–2023)
**Alumnos:** Valentina Carné ​/ Camila Figueroa ​/ Néctor Felipe Ruiz​ / María José Vásquez

**Profesor:** Carlos Pérez

**Curso:** Visualización de Datos y Storytelling

**Dataset:** Our World in Data – Share of Individuals Using the Internet (%)

---


## 🧭 1. Mensaje Central

> Aunque el uso de Internet ha aumentado en todas las regiones del mundo en las últimas décadas, la brecha digital entre África Subsahariana y las regiones más desarrolladas no se reduce; por el contrario, tiende a ampliarse si no existen políticas activas de inclusión digital.

---

## 📂 2. Estructura del Repositorio

```
/notebooks/
    tarea3_storytelling_profesional.ipynb

/data/
    share-of-individuals-using-the-internet.csv

/figures/
    hist_paises_2020.png
    boxplot_paises_2020.png
    series_regiones_WB.png
    brecha_na_ssa.png
    growth_last_10_years_regions.png
    proyeccion_brecha_na_ssa.png
    paises_seleccionados_series.png
    mapa_mundial_2020.png

/ppt/
    Presentacion_Brecha_Digital.pptx

README.md
```

---

## 🎬 3. Framework Narrativo — Estructura en 3 Actos

### **Acto I — Planteamiento**  
Se presenta el contexto global del acceso a Internet: crecimiento sostenido en todas las regiones, pero con puntos de partida muy distintos. Se introduce la pregunta central:  
**¿Convergencia o divergencia digital entre regiones del mundo?**

### **Acto II — Conflicto**  
Evidenciamos la brecha digital entre regiones, especialmente entre **Norteamérica** y **África Subsahariana**. Analizamos diferencias de crecimiento, desigualdad territorial y evolución histórica.

### **Acto III — Resolución**  
Se proyecta la brecha futura, mostrando que no se cerrará de forma natural. Se propone una recomendación accionable para reducir la desigualdad digital.

---

## 📊 4. Visualizaciones Incluidas

Todas las visualizaciones se generan mediante el notebook y se exportan a la carpeta `/figures`.

### **Visualizaciones Exploratorias (EDA):**  
- Histograma de distribución global (2020)  
- Boxplot de variabilidad entre países  
- Series temporales por región (Banco Mundial)  
- Ranking países seleccionados (USA, China, India, Brasil, Sudáfrica)

### **Visualizaciones Explicativas:**  
- Brecha NA–SSA  
- Crecimiento en los últimos 10 años  
- Mapa mundial de conectividad (choropleth)

### **Visualización de Síntesis:**  
- Proyección futura de la brecha digital

Cada visualización incluye:  
✔ Título activo  
✔ Subtítulo con contexto  
✔ Uso estratégico del color  
✔ Anotaciones  
✔ Reducción de ruido  
✔ Consistencia tipográfica  

---

## 🗂️ 5. Dataset y Metadatos

**Fuente:**  
Our World in Data  
https://ourworldindata.org/grapher/share-of-individuals-using-the-internet

**Variables utilizadas:**  
- `Entity`  
- `Code`  
- `Year`  
- `Individuals using the Internet (% of population)`

**Tamaño:** Más de 7.000 observaciones — países y regiones desde 1990 a 2023.

---

## ⚙️ 6. Cómo Reproducir este Proyecto

### **1. Clonar el repositorio**
```bash
git clone https://github.com/<tu_usuario>/tarea3_storytelling_brecha_digital.git
```

### **2. Instalar dependencias**
```bash
pip install pandas numpy matplotlib plotly kaleido
```

### **3. Ejecutar el notebook**
```bash
jupyter notebook notebooks/tarea3_storytelling_profesional.ipynb
```

Las imágenes se guardarán automáticamente en `/figures`.

---

## 📝 7. Recomendación Accionable

Para reducir la brecha digital global se propone:

- Expandir infraestructura de conectividad en regiones rezagadas.  
- Implementar planes de acceso asequible y subsidios.  
- Desarrollar programas de alfabetización digital en zonas rurales.  
- Generar alianzas público–privadas enfocadas en inclusión digital.  

Estas acciones buscan no solo aumentar la conectividad, sino también **cerrar la brecha estructural entre regiones**.

---

# 🤖 8. Declaración de Uso de Herramientas de IA

Declaro que en el desarrollo de esta tarea utilicé herramientas de inteligencia artificial generativa como apoyo para estructurar ideas, mejorar redacción, generar bloques de código, optimizar visualizaciones y organizar secciones del README.

Todo el análisis crítico, interpretación de resultados, selección de visualizaciones, diseño narrativo, toma de decisiones metodológicas y verificación final del contenido fue realizado por mí. La IA actuó exclusivamente como herramienta de apoyo en la generación y ordenamiento de texto y código.

---

# 🔧 9. Lista Completa de Herramientas de IA Utilizadas

**ChatGPT (OpenAI)**  
https://chat.openai.com  
Utilizado para:  
- Sugerencias de estructura narrativa (3 actos)  
- Mejora de redacción y síntesis textual  
- Generación de títulos activos y subtítulos  
- Ajustes en código Python y visualizaciones  
- Redacción del README y declaración de IA  

**ChatGPT – Generación de soporte técnico y depuración**  
https://chat.openai.com  
Utilizado para:  
- Explicaciones de errores de ejecución  
- Optimización y ordenamiento de notebook  
- Inserción de código para exportar imágenes (Plotly + Kaleido)

---

# 📚 10. Bibliografía y Fuentes Complementarias

**Fuentes de datos:**  
- *Our World in Data (OWID)* — “Share of Individuals Using the Internet (%)”  
  https://ourworldindata.org/grapher/share-of-individuals-using-the-internet

**Bibliografía consultada:**  
- Cairo, Alberto. *The Truthful Art: Data, Charts, and Maps for Communication.* New Riders, 2016.  
- Rosling, Hans. *Factfulness.* Flatiron Books, 2018.  
- Munzner, Tamara. *Visualization Analysis and Design.* CRC Press, 2014.  
- The Data Visualization Catalogue. https://datavizcatalogue.com  

---

# 🧠 11. Reflexión Personal

Este proyecto me permitió comprender cómo un análisis exploratorio profundo puede transformarse en una narrativa visual coherente capaz de explicar una problemática global. Además, reforzó la importancia de las visualizaciones como herramienta estratégica para comunicar datos de forma clara, honesta y convincente.
