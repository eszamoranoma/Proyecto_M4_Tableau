# 📺 Streaming is the new TV

> *¿Cuántos de vosotros habéis visto la tele esta semana? ¿Y un stream?*
> *Exacto. Y eso es exactamente de lo que va este proyecto.*

---

## 🎮 ¿De qué va esto?

En julio de 2025, Ibai Llanos reunió **9 millones de personas** viendo una pelea de boxeo en Twitch. Eso es lo que suele tener la final del Mundial de fútbol en televisión. Un streamer español, solo con su canal.

Eso no es una anécdota. Es una tendencia. Y este proyecto lo demuestra con datos.

**Streaming is the new TV** es un análisis del crecimiento del streaming en Twitch entre 2019 y 2025, con especial atención al impacto de la pandemia de COVID-19 y al fenómeno del streaming en español a nivel mundial.

---

## 📊 El dashboard

4 páginas interactivas en Power BI con navegación por botones:

| Página | Qué muestra |
|--------|------------|
| 🟣 **ESLAND** | Top streamers en español, evolución pandemia, géneros y tipos de contenido |
| 🌍 **GLOBAL** | Top streamers mundial, evolución pandemia, géneros y tipos de contenido|
| 🗺️ **Mapa ESLAND** | De dónde son los streamers más vistos en español |
| 🗺️ **Mapa GLOBAL** | De dónde son los streamers más vistos del mundo |

### Algunos datos que te van a sorprender

- 🕐 **4.434 millones de horas** vistas solo en español entre 2019 y 2025
- 👁️ **9 millones de viewers simultáneos** — récord mundial absoluto de Twitch, de un español
- 📈 Las horas vistas en español se **cuadruplicaron en un año** (2019→2020)
- 🌐 El español es el **2º idioma más representado** en el top global de Twitch
- 👩 Solo el **9,4% del contenido** en español lo producen mujeres

---

## 🛠️ Herramientas utilizadas

```
📥 Fuente de datos  →  SullyGnome.com
🐍 Limpieza         →  Python (pandas)
📊 Visualización    →  Power BI Desktop
🧮 Cálculos         →  DAX (medidas calculadas)
```

---

## 📁 Estructura del repositorio

```
Proyecto_M4_PowerBI/
│
├── 📊 dashboard_streamers.pbix       # Dashboard Power BI
│
├── 📂 data/
│   ├── EDA.ipynb                # Jupyter Notebook de exploración y limpieza
│   ├── streamers.csv            # Top 50 streamers en español por año
│   └── streamers_global.csv     # Top 50 streamers global por año
│
└── 📄 README.md
```

---

## 📦 Datasets

Ambos datasets cubren **2019 a 2025** y contienen:

**Variables numéricas:**
`Horas_vistas` · `Viewers_pico` · `Viewers_medios` · `Seguidores_total` · `Seguidores_ganados`

**Variables categóricas:**
`Streamer` · `País` · `Categoria_principal` · `Subcategoria` · `Género` · `Tipo_streamer`

Los datos se obtuvieron de [SullyGnome](https://sullygnome.com), la principal plataforma de estadísticas de Twitch, y se procesaron con Python para unificar los 7 archivos anuales (uno por año) en un único CSV limpio y etiquetado.

--- 

## 💡 Conclusiones

1. **La pandemia no creó el streaming, lo catapultó.** Ya había crecimiento antes de 2020, pero el confinamiento lo convirtió en hábito masivo.

2. **El español tiene un peso global que sorprende.** Somos el 2º idioma de Twitch y tenemos al streamer con más viewers simultáneos de toda la historia de la plataforma.

3. **El streaming ya no es cosa de frikis.** Es entretenimiento, cultura y comunidad. Y compite directamente con la televisión tradicional.

---

## 👩‍💻 Autoras

- Estefania Zamorano Mancilla
- Julia Corada Montano
  
Proyecto realizado como parte del Bootcamp de Data Analytics de **Adalab** — Módulo 4: Visualización de datos con POWER BI

---

*"El streaming es la nueva tele. No porque haya matado a la televisión, sino porque ha creado algo nuevo: entretenimiento en directo, participativo y sin horarios."* 🎙️
