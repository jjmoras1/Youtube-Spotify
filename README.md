# 🎵 Análisis de Tendencias Musicales  

## 📌 Descripción del Proyecto  
Este proyecto analiza las **10 canciones más populares** de diversos artistas utilizando datos de **Spotify y YouTube**. Se han medido diferentes características musicales como:  
- **Danzabilidad**  
- **Energía**  
- **Volumen**  
- **Tiempo de reproducción**  

Además, se han registrado las métricas de reproducción en ambas plataformas para evaluar patrones y tendencias.  

### 📂 **Dataset**  
- **Nombre**: `df_final.csv`  
- **Fuente**: Kaggle - [*Spotify and YouTube Dataset* ](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube) 

---

## 📊 Hipótesis  
Se busca determinar si existe una correlación entre los parámetros de las canciones y su **popularidad en Spotify**. Se analizará si:  
✅ **Las canciones más bailables** tienen más reproducciones que las menos bailables.  
✅ **Las canciones más acústicas** son más populares que las menos acústicas.  
✅ **La duración de la canción influye en su éxito** (más cortas o largas tienen más reproducciones).  

---

## 🎯 **Objetivo Principal**  
Analizar los datos de reproducción de las **10 canciones más populares** de diversos artistas en **Spotify y YouTube** para identificar tendencias de géneros musicales y comparar su éxito en ambas plataformas.  

---

## 🔎 **Alcance**  
Este estudio está dirigido a **interesados en la industria musical**, tales como:  
🎯 **Anunciantes**  
🎧 **Emisoras de radio**  
📻 **Críticos musicales**  

El análisis proporcionará una mejor comprensión de los factores que contribuyen al **éxito de una canción**.  

---

## 📂 **Archivos del Proyecto**  
El proyecto contiene los siguientes notebooks de análisis:  

1️⃣ **`Spoty_youtube.ipynb`** → Notebook principal para la **preparación y análisis inicial** de los datos. Se crea el primer modelo con **todos los datos**.  

2️⃣ **`Test_final_decada.ipynb`** → Se generan modelos diferenciando las canciones por **décadas de lanzamiento**.  

3️⃣ **`Test_final_genero.ipynb`** → Se crean modelos distinguiendo entre **géneros musicales**.  

4️⃣ **`Test_final_Clustergenero.ipynb`** → Se agrupan canciones en **clusters de géneros** para mejorar el análisis de tendencias.  

📌 **Se recomienda ejecutar los notebooks en este orden.**  

---

## 🚀 **Cómo Usar el Proyecto**  
1. Clona este repositorio:  
   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
