# 🏋️ Laboratorios de Fisiología del Ejercicio — Python en Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vgarrido1995/fisiologia-ejercicio-colab/blob/main/zonas_running_5min.ipynb)

> Repositorio de notebooks interactivos para el aprendizaje de fisiología del ejercicio aplicada con Python.  
> Universidad — Pregrado en Ciencias del Deporte

---

## 📁 Contenido del repositorio

| Archivo | Descripción | Abrir en Colab |
|---------|-------------|----------------|
| `zonas_running_5min.ipynb` | Zonas de entrenamiento en running desde test de 5 min (VAM) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vgarrido1995/fisiologia-ejercicio-colab/blob/main/zonas_running_5min.ipynb) |
| `zonas_ciclismo_5min.ipynb` | Zonas de entrenamiento en ciclismo desde test de 5 min (PAM) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vgarrido1995/fisiologia-ejercicio-colab/blob/main/zonas_ciclismo_5min.ipynb) |
| `potencia_critica_colab.ipynb` | Cálculo de Potencia Crítica (CP) y W' | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vgarrido1995/fisiologia-ejercicio-colab/blob/main/potencia_critica_colab.ipynb) |

---

## 🚀 ¿Cómo usar estos notebooks?

### Opción A — Directamente en el navegador (recomendada)
1. Haz clic en el botón **"Open in Colab"** del notebook que quieras usar
2. Se abrirá automáticamente en Google Colab (necesitas una cuenta Google)
3. Ve a **Archivo → Guardar una copia en Drive** para tener tu propia versión editable
4. Ejecuta las celdas en orden con `Shift + Enter` o el botón ▶
5. **Solo edita la Celda 3** con tus propios datos

### Opción B — Descargar y subir manualmente
1. Haz clic en el archivo `.ipynb` que quieras
2. Descárgalo con el botón **Download raw file** (ícono ↓)
3. Ve a [colab.research.google.com](https://colab.research.google.com)
4. Selecciona **Subir → elige el archivo descargado**

---

## 📓 Descripción de cada notebook

### 🏃 `zonas_running_5min.ipynb`

Calcula las **zonas de entrenamiento en running** a partir del test de campo de 5 minutos.

**¿Qué necesitas ingresar?**
- Nombre del atleta
- Peso corporal (kg)
- Distancia recorrida en 5 minutos (metros)

**¿Qué obtienes?**
- VAM (Velocidad Aeróbica Máxima) en km/h y m/min
- VO₂máx estimado (ml/kg/min)
- **5 zonas de entrenamiento** expresadas en:
  - Velocidad (km/h)
  - Ritmo (min/km)
  - Paso en 400 metros (min:seg)
- Gráfico de zonas
- Exportación a CSV y Excel

---

### 🚴 `zonas_ciclismo_5min.ipynb`

Calcula la **PAM (Potencia Aeróbica Máxima)** y las **zonas de entrenamiento en ciclismo** a partir de la potencia media en un test de 5 minutos con medidor de potencia.

**¿Qué necesitas ingresar?**
- Nombre del atleta
- Peso corporal (kg)
- Potencia media en el test de 5 minutos (Watts)

**¿Qué obtienes?**
- PAM estimada (W y W/kg)
- FTP estimado (~76% de P5min)
- VO₂máx estimado (ml/kg/min)
- Categoría de rendimiento (según escala W/kg de Coggan)
- **6 zonas de entrenamiento** en Watts absolutos y W/kg
- Gráfico de zonas con líneas de PAM y FTP
- Exportación a Excel (2 hojas) y CSV

---

### 📊 `potencia_critica_colab.ipynb`

Calcula la **Potencia Crítica (CP)** y la **Capacidad de Trabajo Anaeróbico (W')** usando el modelo hiperbólico ajustado por mínimos cuadrados. Permite comparar el ajuste con 2, 3 o más puntos.

---

## 🐍 Introducción a la programación — ¿Por qué Python?

Estos notebooks no son solo herramientas de cálculo: están diseñados para que vayas aprendiendo conceptos de programación mientras los usas.

### Conceptos que aprenderás en estos notebooks

| Concepto | ¿Dónde aparece? | ¿Para qué sirve? |
|----------|-----------------|------------------|
| **Variables** | Celda 3 de todos los notebooks | Almacenar datos en memoria |
| **Tipos de datos** | `str`, `int`, `float` en Celda 3 | Distinguir texto de números |
| **Funciones (`def`)** | Celda 2 de todos | Reutilizar código, evitar repetición |
| **Bucles (`for`)** | Celdas de tablas y gráficos | Operar sobre múltiples elementos |
| **Condicionales (`if/elif/else`)** | Clasificación de rendimiento | Tomar decisiones en el código |
| **Diccionarios (`dict`)** | Definición de zonas | Agrupar datos relacionados |
| **DataFrames (pandas)** | Celdas de exportación | Manejar tablas de datos |
| **Gráficos (matplotlib)** | Celdas de visualización | Comunicar resultados visualmente |
| **f-strings** | Todas las celdas de output | Formatear texto con variables |

### ¿Por qué aprender esto como estudiante de Ciencias del Deporte?

- **Automatización:** Aplica los mismos cálculos a 30 atletas en segundos
- **Reproducibilidad:** Comparte tu código y cualquiera puede verificar tu análisis
- **Visualización:** Genera gráficos publicables con pocas líneas
- **Carrera profesional:** Cada vez más clubes y centros de rendimiento usan análisis de datos
- **Base para más:** Una vez que dominas estos fundamentos, puedes aprender machine learning aplicado al deporte, análisis de GPS, etc.

### Recursos para seguir aprendiendo Python

- [Python para todos (en español)](https://www.py4e.com/book) — libro gratuito
- [Kaggle Learn Python](https://www.kaggle.com/learn/python) — cursos gratuitos con ejercicios
- [Google Colab — tutorial oficial](https://colab.research.google.com/notebooks/intro.ipynb)

---

## 🔬 Referencias científicas

- Billat, V.L. (2001). Interval training for performance. *Sports Medicine*, 31(1), 13–31.
- Coggan, A.R. (2003). *Training and Racing with a Power Meter*. VeloPress.
- Hawley, J.A. & Noakes, T.D. (1992). Peak power output predicts maximal oxygen uptake. *European Journal of Applied Physiology*, 65, 79–83.
- Léger, L. & Bouchard, C. (1980). Aerobic performance. *Canadian Journal of Applied Sport Sciences*, 5, 9–17.
- Morton, R.H., Billat, L.V. (2004). The critical power model. *Journal of Sports Sciences*, 22, 889–897.

---

## 📬 Contacto

**Valentín Garrido**  
GitHub: [@vgarrido1995](https://github.com/vgarrido1995)

---

*Los notebooks son de uso libre con fines educativos. Si los usas en tu curso o institución, ¡se agradece una estrella ⭐ al repositorio!*
