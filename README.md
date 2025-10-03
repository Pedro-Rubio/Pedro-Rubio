# 👋 ¡Hola! Soy Pedro Rubio

[![Data Analyst](https://img.shields.io/badge/Data%20Analyst-Blueviolet?style=for-the-badge&logo=powerbi)](https://www.linkedin.com/in/srdelosdatos)  

**Analista de Datos | Data Scientist en Formación**  

📍 **Buenos Aires, Argentina**  

¡Transformo datos crudos en **decisiones accionables** que impulsan negocios! Me apasiona la **analítica orientada a resultados**, con foco en **HR Analytics**, **detección de fraude** y **optimización operativa**. Diseño dashboards intuitivos, construyo ETL eficientes y desarrollo modelos predictivos simples pero impactantes – siempre priorizando el **valor para el negocio** sobre la complejidad técnica.  

Mi mantra: **Claridad > Complejidad | Automatización > Manualidad | Impacto > Métricas vacías**.  

> ✨ **Diferencial**: Entender el negocio primero, los algoritmos después. ¡Hagamos que tus datos cuenten historias que vendan!  

---

## 🔍 **¿Qué hago (y por qué brilla)?**  

- **Dashboards ejecutivos**: Creo visualizaciones en Power BI/Tableau que la gerencia no solo entiende, sino que *usa diariamente* para tomar decisiones.  
- **Pipelines ETL robustos**: Automatizo limpieza y transformación con Python/SQL, asegurando reproducibilidad y escalabilidad.  
- **Modelos predictivos prácticos**: Abordo problemas reales como rotación de personal, scoring de fraude o ausentismo – con énfasis en interpretabilidad (SHAP) y métricas business-friendly (PR-AUC, F1, costo de errores).  
- **Data Storytelling**: Convierto insights técnicos en narrativas claras para stakeholders no-tech, impulsando acciones medibles.  
- **Análisis de impacto**: Evalúo no solo precisión, sino ROI: ¿reduce costos? ¿mejora recall sin inflar falsos positivos?  

> 📊 **Dato clave**: En proyectos reales, he reducido tiempos de reporting en un 40% y mejorado recall en scoring hasta +12 pts.  

---

## 🛠️ **Stack Técnico (Activo & Evolucionando)**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=flat&logo=Power-BI&logoColor=black)  

| Categoría | Herramientas Principales | Nivel |
|-----------|---------------------------|-------|
| **Lenguajes** | Python, SQL, R (básico) | 🟢 Avanzado |
| **Análisis & ML** | pandas, NumPy, scikit-learn, seaborn, matplotlib | 🟢 Avanzado |
| **Visualización** | Power BI (DAX), Tableau, Excel Avanzado | 🟢 Avanzado |
| **ETL & Automatización** | Python Scripts, Git, GitHub Actions (básico) | 🟡 Intermedio |
| **Plataformas** | Microsoft Fabric, Databricks (en aprendizaje) | 🟡 Intermedio |
| **Cloud** | Azure (S3, SageMaker explorando), AWS basics | 🟡 Principiante |

> ⚠️ **Transparencia**: No domino aún Kubernetes, Spark en prod o MLOps full-stack – pero estoy en camino con proyectos hands-on. ¡Sigo aprendiendo!  

---

## 🚀 **Proyectos Destacados** 

Aquí van mis creaciones más impactantes – todos con datos sintéticos/anonimizados para respetar NDAs y privacidad. ¡Clona, corre y experimenta!  

### 1) Detección de Fraude en Transacciones **QR** *(MVP en desarrollo — mi estrella actual)*
- **Desafío:** reducir **falsos positivos** en pagos digitales sin perder capacidad de detección (≈10k transacciones sintéticas).
- **Qué construí:** **ETL** completo (Python/SQL), **feature engineering** (patrones temporales, **señales geográficas agregadas**, comportamiento usuario/comercio), modelo **scikit-learn** (Random Forest + **threshold tuning**), **app Streamlit** para triage (ALTO/REVISAR/OK) y **dashboard Power BI** con KPIs operativos.
- **Impacto (rangos):** **+5 a +12 pts PR-AUC** vs baseline; **–15% a –35% FPR**; priorización de revisiones por **expected loss** (*prob* × *monto*).
  
- **Por qué mirarlo:** pipeline **end-to-end** (de data messy a decisiones), ideal para fintech/operaciones.

### 2) Detección de Fraude en **Tarjetas de Crédito** *(prototipo reproducible)*
- **Desafío:** detectar transacciones fraudulentas en **clase desbalanceada** con costos operativos diferenciados.
- **Qué construí:** **EDA y ETL** (limpieza, reglas de negocio), **features** de monto/velocidad/merchant/horario, modelos **Logistic Regression / XGBoost** con **calibración** y evaluación por **PR-AUC, ROC-AUC, F1**, además de **curvas costo-beneficio**; **Power BI** para FPR/FNR por segmento y cola de casos.
- **Impacto (rangos):** **+6 a +10 pts PR-AUC** vs baseline; **recall** mantenido con **FPR** acotado mediante **thresholds por segmento**.
  
- **Por qué mirarlo:** muestra **trade-offs** reales (precision/recall) y cómo **operativizar** un scoring en revisión manual limitada (**precision@k**).

### 3) Analítica de **RR.HH.** — Predicción de Rotación *(basado en experiencia real)*
- **Desafío:** identificar factores de abandono voluntario y dar **visibilidad ejecutiva** (rotación, ausentismo, costo).
- **Qué construí:** **modelo de datos + ETL** (Excel/SQL), **dashboards Power BI (DAX)** con **drill-down** por área/sucursal, y **regresión logística + SHAP** para explicabilidad y priorización de retención.
- **Impacto (demo):** **F1 ≈0.80–0.84** en datos sintéticos; set de **KPIs estandarizados** y frecuencia de reporte **mensual/semanal**.
  
- **Por qué mirarlo:** combina **conocimiento de dominio** en HR con ML **interpret-able** y tableros accionables.

### 4) **Expansión Pharma (Biogenesis)** — Analytics Estratégico *(bonus)*
- **Desafío:** priorizar mercados LATAM post-COVID con datos epidemiológicos (≈12M filas).
- **Qué construí:** **Power Query/Power BI** para ETL, **DAX** para KPIs y segmentación por país/línea; storytelling con mapas y tendencias.
  
- **Por qué mirarlo:** caso de **inteligencia de mercado** con alto volumen y foco en **decisión ejecutiva**.

---

### ✍️ Nota rápida sobre reproducibilidad
- Repos con **notebooks explicados paso a paso**, **scripts de ETL** y estructura clara (`/data`, `/notebooks`, `/src`, `/powerbi`, `/docs`).
- Evaluación con **PR-AUC/ROC-AUC, F1, FPR/FNR, precision@k** y **threshold tuning** guiado por **costo-beneficio**.
- Demos públicas **sin PII** y métricas **en rangos** (NDA).


> 📌 **Explora más**: Todos los repos incluyen notebooks comentados paso a paso, requirements.txt y data quality checks. ¡Forkea y contribuye!  

---

## 📂 **Qué Encontrarás en Mis Repos**  

- **Notebooks narrativos**: No solo código – explico *por qué* cada paso, con visuals y business context.  
- **Dashboards interactivos**: Embeddables, con drill-downs y alertas.  
- **Scripts ETL**: Reproducibles, versionados con Git, listos para prod.  
- **Proyectos de aprendizaje**: De Henry, Kaggle challenges y freelance – siempre con foco en impacto medible.  

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Pedro-Rubio&show_icons=true&theme=radical)  


---

## 📬 **¡Conectemos! Vamos a Colaborar**  
Estoy abierto a freelances en fraude/HR analytics, mentorship o coffee chats virtuales. ¿Un proyecto en mente? ¡Escribime!  

- 🔗 **LinkedIn**: [linkedin.com/in/srdelosdatos](https://www.linkedin.com/in/srdelosdatos)  
- 📧 **Email**: [rubio-pedro@hotmail.com](mailto:rubio-pedro@hotmail.com)  
 

> _“Los datos no hablan solos. Mi trabajo es darles voz, claridad y propósito – para que tu negocio gane.”_ – Pedro Rubio  

---

*Última actualización: Octubre 2025 | ¡Gracias por visitar! ⭐ Si te gusta, dame una star o feedback en issues.*
