# Estanislao Molinas

**AI Product Manager (B2B & B2C) · Software Developer · B2G Consultant**

Registered Product Owner™ (RPO) and Registered Scrum Master™ (RSM) — Scrum Inc. · Google Project Management Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/estanislao-molinas-4057ba1b8/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:estanislao.molinasir@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-6671-854X)
[![Portfolio B2G](https://img.shields.io/badge/Portfolio_B2G-000000?style=flat&logo=googlechrome&logoColor=white)](https://estanislaomolinasb2g.com/)

🇪🇸 [Versión en español](#español)

## Featured project

### [series-ar-qlora](https://github.com/estanimolinas/series-ar-qlora)

An agent that answers questions about official Argentine time series by querying the datos.gob.ar API with three tools. The project fine-tunes a small language model (Qwen3-4B, 4-bit) with QLoRA and compares it with the same model without fine-tuning.

- **Test result** (585 questions from 23 dataset families absent from training): 28.4% → 72.8% correct answers. Difference of +44.4 points; 95% interval resampling by family: +37.2 to +51.9.
- **Evaluation design:** family-based split to prevent leakage, a custom evaluator validated with an oracle agent and negative controls, test set evaluated once per model.
- **Engineering:** 128 tests, continuous integration with GitHub Actions, reproducible environment with `uv`, documented API costs.
- **Documented limitations** in the README: one training seed, asymmetric prompts between models, questions generated with a language model.

## Skills

Product vision and strategy · Backlog prioritization and roadmapping · Scrum / Agile ceremonies · Product discovery → delivery · A/B testing and experimentation · Data analytics applied to product (SQL) · User-experience-oriented design · Stakeholder management

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

**Stack:** Python · R · SQL · HTML5 · Git · Claude Code · SQLite (FTS5) · Unsloth / QLoRA · pytest · GitHub Actions
**Methodologies:** Scrum · Agile · Kanban
**Currently learning:** API integration · Flask · Claude Agent SDK · CI/CD · product analytics tools (Google Analytics, Amplitude, Mixpanel)

## Experience

- **Software Developer — Colonia Suiza** (Jul 2026–present). Innovation Team, IT Department. Hybrid role between software development and product management. R+D of innovative solutions into products and microservices for the claims (insurance) business, across 4 business verticals.
- **Instructor, "AI Tools for Political Scientists and International Relations Professionals" workshop — Diplomacia Activa** (Jun 2026–present, remote). Training on LLMs (Claude) and NotebookLM for Political Science, International Relations and Social Sciences use cases.
- **AI Product Manager — Project Copilot LLC** (May 2026–present, US, remote). Sprint kickoffs, backlog prioritization, Scrum facilitation. Claude + Atlassian MCP (Rovo) against the GitHub repository to audit sprints and draft epics and user stories.
- **B2G Consultant — ASSAL** (Oct 2025–Jul 2026, Santa Fe Province Ministry of Health). Digitalization of the Food Handling Certification course from scratch (1,000+ users on Moodle) and the roadmap for 15 educational videos (HeyGen).
- **AI-Driven Operations Manager — Zagged** (Mar–May 2026, NYC, remote). Management of 35+ concurrent international campaigns, cutting delivery time by 30%. Notion Agents and a Claude Skill.md for automated reporting.
- **Junior SEO Analyst — Refindable** (Jan–Sep 2025, US, remote). SEO performance and content for clients in the US and Australia. Google Search Console → Looker Studio integration for KPI reporting. QA testing of a pre-trained LLM for SEO article writing.
- **AI Product Manager Trainee — Project Copilot** (Apr 2024–Jan 2025, Santa Fe, remote). Full product cycle (discovery → delivery) with the CTO and PM, applying Scrum and Kanban. SOPs documented to standardize team workflows.

## Education

- Specialization and Master's in Data Mining — UTN Santa Fe (2026–2029, in progress)
- Bachelor's in International Relations — UCSF (2022–2026), GPA 9.31/10. Thesis (grade: 10): "The Development of Artificial Intelligence in Cyberspace: US-China Bilateral Relations, 2017-2025"
- Exchange semester in Global Law and Transnational Studies — Università degli Studi di Torino (2023–2024)
- Business Track / AI Agency — Golem Lab AI (2026, in progress)
- Empower Digital Product Leaders™ — ITtude, intensive Product Management mentorship (Apr–Jul 2026)

## Certifications

Google Project Management Professional Certificate — Coursera (Jan 2025) · Registered Product Owner™ (RPO) and Registered Scrum Master™ (RSM) — Agile Education by Scrum Inc. · Product Manager Flex — Coderhouse · Claude Code in Action — Anthropic · Claude 101 — Anthropic · How Transformer LLMs Work — DeepLearning.AI · Introduction to Python — DataCamp · EF SET English Certificate — C1 Advanced (67/100)

---

## Español

**AI Product Manager (B2B y B2C) · Desarrollador de software · Consultor B2G**

Registered Product Owner™ (RPO) y Registered Scrum Master™ (RSM) — Scrum Inc. · Google Project Management Professional

## Proyecto destacado

### [series-ar-qlora](https://github.com/estanimolinas/series-ar-qlora)

Agente que responde preguntas sobre series de tiempo oficiales de Argentina consultando la API de datos.gob.ar con tres herramientas. El proyecto ajusta con QLoRA un modelo de lenguaje de tamaño reducido (Qwen3-4B, 4 bits) y lo compara con el mismo modelo sin ajustar.

- **Resultado en test** (585 preguntas de 23 familias de datasets ausentes del entrenamiento): 28,4 % → 72,8 % de respuestas correctas. Diferencia de +44,4 puntos; intervalo del 95 % remuestreando por familia: +37,2 a +51,9.
- **Diseño de la evaluación:** partición por familias para evitar fuga entre entrenamiento y prueba, evaluador propio validado con un agente oráculo y controles negativos, test evaluado una sola vez por modelo.
- **Ingeniería:** 128 tests, integración continua con GitHub Actions, entorno reproducible con `uv`, costos de la API documentados.
- **Limitaciones documentadas** en el README: una semilla de entrenamiento, prompts asimétricos entre modelos y preguntas generadas con un modelo de lenguaje.

## Habilidades

Visión y estrategia de producto · Priorización de backlog y roadmap · Ceremonias Scrum / Agile · Product discovery → delivery · A/B testing y experimentación · Analítica de datos aplicada a producto (SQL) · Diseño orientado a la experiencia de usuario · Gestión de stakeholders

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

**Stack:** Python · R · SQL · HTML5 · Git · Claude Code · SQLite (FTS5) · Unsloth / QLoRA · pytest · GitHub Actions
**Metodologías:** Scrum · Agile · Kanban
**En desarrollo:** integración de APIs · Flask · Claude Agent SDK · CI/CD · herramientas de analítica de producto (Google Analytics, Amplitude, Mixpanel)

## Experiencia

- **Software Developer — Colonia Suiza** (jul. 2026–actualidad). Equipo de Innovación, Departamento IT. Rol híbrido entre desarrollo y product management. Innovación en productos y microservicios para gerencia de siniestros, 4 verticales de negocio.
- **Profesor, taller "Herramientas de IA para politólogos e internacionalistas" — Diplomacia Activa** (jun. 2026–actualidad, remoto). Formación en LLMs (Claude) y NotebookLM para casos de uso de Ciencia Política, RRII y Ciencias Sociales.
- **AI Product Manager — Project Copilot LLC** (may. 2026–actualidad, US, remoto). Sprint kickoffs, priorización de backlog, facilitación Scrum. Uso de Claude + MCP de Atlassian (Rovo) contra el repositorio de GitHub para auditar sprints y redactar epics y user stories.
- **Consultor B2G — ASSAL** (oct. 2025–jul. 2026, Ministerio de Salud de Santa Fe). Digitalización desde cero del curso de Certificación en Manipulación de Alimentos (+1.000 usuarios en Moodle) y roadmap de 15 videos educativos (HeyGen).
- **AI-Driven Operations Manager — Zagged** (mar.–may. 2026, NYC, remoto). Gestión de 35+ campañas internacionales concurrentes, con una reducción del 30 % en el tiempo de entrega. Notion Agents y un Claude Skill.md para reporting automatizado.
- **Junior SEO Analyst — Refindable** (ene.–sept. 2025, US, remoto). Gestión de SEO performance y contenido para clientes de USA y Australia. Integración Google Search Console → Looker Studio para reporting de KPIs. QA de un LLM preentrenado para redacción de artículos SEO.
- **AI Product Manager Trainee — Project Copilot** (abr. 2024–ene. 2025, Santa Fe, remoto). Ciclo completo de producto (discovery → delivery) junto al CTO y el PM, con Scrum y Kanban. SOPs documentados para estandarizar los workflows del equipo.

## Educación

- Especialización y Maestría en Minería de Datos — UTN Regional Santa Fe (2026–2029, en curso)
- Licenciatura en Relaciones Internacionales — UCSF (2022–2026), promedio 9,31. Tesis (10): "El Desarrollo de la Inteligencia Artificial en el Ciberespacio: La Relación Bilateral de los Estados Unidos y China entre 2017-2025"
- Intercambio en Global Law and Transnational Studies — Università degli Studi di Torino (2023–2024)
- Track de Negocios / AI Agency — Golem Lab AI (2026, en curso)
- Empower Digital Product Leaders™ — ITtude, mentoría intensiva de Product Management (abr.–jul. 2026)

## Certificaciones

Google Project Management Professional Certificate — Coursera (ene. 2025) · Registered Product Owner™ (RPO) y Registered Scrum Master™ (RSM) — Agile Education by Scrum Inc. · Product Manager Flex — Coderhouse · Claude Code in Action — Anthropic · Claude 101 — Anthropic · How Transformer LLMs Work — DeepLearning.AI · Introduction to Python — DataCamp · EF SET English Certificate — C1 Advanced (67/100)
