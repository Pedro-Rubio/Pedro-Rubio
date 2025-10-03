# 👋 ¡Hola! Soy Pedro Rubio

[![Data Analyst](https://img.shields.io/badge/Data%20Analyst-Blueviolet?style=for-the-badge&logo=powerbi)](https://www.linkedin.com/in/srdelosdatos)  
**Analista de Datos | Data Scientist en Formación**  
📍 **Buenos Aires, Argentina**  

¡Transformo datos crudos en **decisiones accionables** que impulsan negocios! Me apasiona la **analítica orientada a resultados**, con foco en **HR Analytics**, **detección de fraude** y **optimización operativa**. Diseño dashboards intuitivos, construyo ETL eficientes y desarrollo modelos predictivos simples pero impactantes – siempre priorizando el **valor para el negocio** sobre la complejidad técnica.  

Actualmente, finalizo mi bootcamp en **Data Analysis (Henry, julio 2025)** y mi **Ingeniería Industrial (UTN, diciembre 2024)**. Mi mantra: **Claridad > Complejidad | Automatización > Manualidad | Impacto > Métricas vacías**.  

> ✨ **Superpoder**: Entender el negocio primero, los algoritmos después. ¡Hagamos que tus datos cuenten historias que vendan!  

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
| **Visualización** | Power BI (DAX), Tableau, Excel Avanzado | 🟢 Experto |
| **ETL & Automatización** | Python Scripts, Git, GitHub Actions (básico) | 🟡 Intermedio |
| **Plataformas** | Microsoft Fabric, Databricks (en aprendizaje) | 🟡 Intermedio |
| **Cloud** | Azure (S3, SageMaker explorando), AWS basics | 🟡 Principiante |

> ⚠️ **Transparencia**: No domino aún Kubernetes, Spark en prod o MLOps full-stack – pero estoy en camino con proyectos hands-on. ¡Sigo aprendiendo!  

---

## 🚀 **Proyectos Destacados**  
Aquí van mis creaciones más impactantes – todos con datos sintéticos/anonimizados para respetar NDAs y privacidad. ¡Clona, corre y experimenta!  

### 1. **Detección de Fraude en Transacciones QR** *(MVP en Desarrollo – Mi Estrella Actual)*  
   - **Desafío**: Reducir falsos positivos en pagos digitales sin sacrificar detección de fraudes reales (dataset sintético de 10k transacciones).  
   - **Lo que construí**: ETL completo (Python/SQL), feature engineering (geolocalización, patrones temporales, comportamiento usuario), modelo con scikit-learn (Random Forest + threshold tuning), y app Streamlit para triage por riesgo (ALTO/REVISAR/OK). Dashboard Power BI con KPIs en tiempo real.  
   - **Impacto**: +10 pts en PR-AUC, -25% en FPR vs. baseline; prioriza revisiones por "expected loss" (prob × monto).  
   - 🔗 **[Notebook ETL & Modelado](https://github.com/Pedro-Rubio/Proyecto_Fraude/blob/main/Proyecto_Data_Fraude_Depurado.ipynb)** | **[Demo Streamlit](https://streamlit.io/cloud?app=tu-app-url-aqui)** | **[Dashboard Power BI](https://app.powerbi.com/view?r=eyJrIjoi...")**  
   - 🏆 **Por qué mirarlo**: End-to-end desde data messy a deploy – ideal para fintech.  

### 2. **Predicción de Rotación en RR.HH.** *(Inspirado en mi Experiencia en Hard Rock Cafe)*  
   - **Desafío**: Predecir abandonos voluntarios para reducir costos de contratación (dataset sintético de 5k empleados).  
   - **Lo que construí**: EDA con pandas, segmentación (área/antigüedad), regresión logística + SHAP para explicabilidad, y recomendaciones accionables (e.g., alertas tempranas).  
   - **Impacto**: Identificó factores clave (salario equity, carga laboral) con F1-score 0.82; simulación: -15% rotación en alto riesgo.  
   - 🔗 **[Notebook Completo](https://github.com/Pedro-Rubio/HR-Rotacion-Analysis – agrega si lo subes!)**  
   - 🏆 **Por qué mirarlo**: Mezcla HR domain knowledge con ML simple – transferable a scoring de candidatos.  

### 3. **Bonus: Expansión Pharma (Biogenesis)** *(Analytics Estratégico)*  
   - Análisis de datos epidemiológicos (12M rows) para priorizar mercados LATAM post-COVID. ETL en Power Query, dashboards con DAX.  
   - 🔗 **[Repo](https://github.com/Pedro-Rubio/Biogenesis)**  

> 📌 **Explora más**: Todos los repos incluyen notebooks comentados paso a paso, requirements.txt y data quality checks. ¡Forkea y contribuye!  

---

## 📂 **Qué Encontrarás en Mis Repos**  
- **Notebooks narrativos**: No solo código – explico *por qué* cada paso, con visuals y business context.  
- **Dashboards interactivos**: Embeddables, con drill-downs y alertas.  
- **Scripts ETL**: Reproducibles, versionados con Git, listos para prod.  
- **Proyectos de aprendizaje**: De Henry, Kaggle challenges y freelance – siempre con foco en impacto medible.  

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Pedro-Rubio&show_icons=true&theme=radical)  
*(Agrega tu token para stats reales – opcional para más engagement!)*  

---

## 📬 **¡Conectemos! Vamos a Colaborar**  
Estoy abierto a freelances en fraude/HR analytics, mentorship o coffee chats virtuales. ¿Un proyecto en mente? ¡Escribime!  

- 🔗 **LinkedIn**: [linkedin.com/in/srdelosdatos](https://www.linkedin.com/in/srdelosdatos)  
- 📧 **Email**: [rubio-pedro@hotmail.com](mailto:rubio-pedro@hotmail.com)  
- 🌐 **Portfolio Web**: [En Construcción – Próximamente en Notion/GitHub Pages](https://pedro-rubio.notion.site)  
- 🐦 **X/Twitter**: [@srdelosdatos](https://x.com/srdelosdatos) *(Agrega si lo tienes!)*  

> _“Los datos no hablan solos. Mi trabajo es darles voz, claridad y propósito – para que tu negocio gane.”_ – Pedro Rubio  

---

*Última actualización: Octubre 2025 | ¡Gracias por visitar! ⭐ Si te gusta, dame una star o feedback en issues.*
