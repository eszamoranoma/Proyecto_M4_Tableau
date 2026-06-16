# Proyecto_M4_Tableau


## Sobre el Dataset

### 🎓 Impacto de la IA en Estudiantes — Dataset Académico y de Bienestar
Un dataset exhaustivo que recoge cómo el uso de herramientas de IA Generativa influye en el rendimiento académico, el desarrollo de habilidades, la salud mental y el riesgo de burnout en 50.000 estudiantes.
### 📌 Sobre el Dataset
A medida que herramientas de IA Generativa como ChatGPT, Copilot y Gemini se integran cada vez más en la vida académica, entender su impacto real en los estudiantes es más importante que nunca. Este dataset ofrece una visión rica y multidimensional de la interacción de los estudiantes con la IA, abarcando resultados académicos, patrones de comportamiento, contexto institucional y bienestar psicológico.
Tanto si eres investigador, educador, científico de datos o responsable de políticas, este dataset es un terreno fértil para explorar los beneficios y riesgos de la adopción de la IA en la educación superior.

## 📊 Resumen del Dataset
PropiedadDetallesFilas50.000 estudiantesColumnas16 variablesValores nulosNinguno (dataset completo)FormatoCSVVariables objetivoPost_Semester_GPA, Skill_Retention_Score, Burnout_Risk_Level

🗂️ Descripción de las Columnas
### 🪪 Identificador
ColumnaTipoDescripciónStudent_IDEnteroIdentificador numérico único por estudiante (100001–150000)
### 🎓 Perfil Académico
ColumnaTipoDescripciónMajor_CategoryCategóricaCampo de estudio: STEM, Empresariales, Humanidades, Medicina, ArtesYear_of_StudyCategóricaCurso académico: Primer año, Segundo, Tercero, Cuarto, PosgradoPre_Semester_GPADecimalNota media al inicio del semestre (~1,18 – 4,00)Post_Semester_GPADecimalNota media al final del semestre (~1,00 – 4,00) — variable objetivo principal
### 🤖 Comportamiento de Uso de IA
ColumnaTipoDescripciónWeekly_GenAI_HoursDecimalHoras semanales promedio usando IA Generativa (0 – 40 h)Primary_Use_CaseCategóricaUso principal de la IA: Redacción, Resumen de lecturas, Depuración de código, Generación de ideas, Respuestas directasPrompt_Engineering_SkillCategóricaNivel autopercibido en el diseño de prompts: Principiante, Intermedio, AvanzadoTool_DiversityEnteroNúmero de herramientas de IA distintas utilizadas (1–5)Paid_SubscriptionBooleanoSi el estudiante tiene suscripción de pago (Sí / No)
### 📚 Hábitos de Estudio
ColumnaTipoDescripciónTraditional_Study_HoursDecimalHoras semanales de estudio tradicional (sin IA) (1 – ~36 h)Perceived_AI_DependencyEnteroDependencia autopercibida de la IA, del 1 (baja) al 10 (alta)
### 🏛️ Contexto Institucional
ColumnaTipoDescripciónInstitutional_PolicyCategóricaPostura oficial de la institución: Permitido con cita, Prohibición estricta, Uso activamente fomentado
### 🧠 Salud Mental y Bienestar
ColumnaTipoDescripciónAnxiety_Level_During_ExamsEnteroNivel de ansiedad en exámenes (autopercibido), del 1 (mínimo) al 10 (severo)Skill_Retention_ScoreDecimalPuntuación (0–100) sobre retención de conocimientos al finalizar el semestreBurnout_Risk_LevelCategóricaRiesgo de burnout: Bajo, Medio, Alto

## 📈 Estadísticas Clave
VariableMínMediaMáxGPA Pre-semestre1,183,154,00GPA Post-semestre1,003,354,00Horas semanales de IA0,008,4340,00Horas de estudio tradicional1,0011,2135,86Puntuación de retención10,7875,80100,00Dependencia percibida de IA13,5110Nivel de ansiedad14,2710

## 💡 Posibles Usos
### 📉 Análisis de cambio en GPA — ¿Cómo se correlaciona el uso de IA con la mejora o el descenso académico?

### 🧩 Predicción de burnout — Construir un clasificador para predecir el nivel de burnout a partir de hábitos de estudio y uso de IA.

### 🔍 Modelado de retención de habilidades — ¿Perjudica el uso intensivo de IA la retención de conocimientos a largo plazo?

### 🏛️ Estudio de impacto de políticas — Comparar resultados bajo distintas políticas institucionales de IA.

### 🧠 Insights de salud mental — Explorar vínculos entre dependencia de IA, ansiedad y burnout.

### 🎓 Tendencias por carrera y curso — ¿Qué disciplinas se benefician más (o sufren más) de la adopción de IA?

### ⚡ Prima del prompt engineering — ¿Superan en rendimiento los estudiantes con habilidades avanzadas en prompts?

### 🔑 Variables Objetivo Sugeridas
ObjetivoColumnaRegresiónPost_Semester_GPA, Skill_Retention_ScoreClasificaciónBurnout_Risk_LevelAnálisisPerceived_AI_Dependency, Anxiety_Level_During_Exams

## 🧹 Calidad de los Datos
✅ Sin valores nulos en las 50.000 filas y 16 columnas

✅ Codificación consistente en todas las variables categóricas

✅ Representación equilibrada entre carreras, cursos y políticas

✅ Listo para usar — no requiere preprocesamiento para análisis básicos

## 📜 Licencia
Por favor, revisa la licencia del dataset antes de usarlo. Cita correctamente si lo utilizas en proyectos académicos o comerciales.
### 🙏 Agradecimientos
Si usas este dataset en tu trabajo, considera dejar un voto positivo y un comentario describiendo tu análisis. ¡El feedback de la comunidad ayuda a mejorar futuras versiones!
¡Feliz análisis! 🚀
