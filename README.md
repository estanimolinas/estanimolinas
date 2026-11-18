<div align="center">
<img src="assets/banner.svg" alt="Estanislao Molinas — Junior AI & Data Engineer: AI agents, RAG, data pipelines, evaluation" width="100%">
</div>

Junior AI & Data Engineer working in insurance claims management. The role blends AI engineering, data engineering and product thinking: LLM agents and their harnesses (tools, context and evaluation), RAG systems and knowledge bases, and data pipelines that make reliable data available to the BI team. Each solution is owned end to end, from understanding the pain point to shipping it and measuring the result. Earlier roles in product management, data analytics and public-sector consulting shape how scope is defined, prioritized and measured.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/estanislao-molinas-4057ba1b8/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:estanislao.molinasir@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-6671-854X)

🇦🇷 [Versión en español](#español)

## Scope of work

- **AI:** LLM agents and harnesses (tool use, context, evaluation), RAG and knowledge bases, QLoRA fine-tuning, agent observability with Langfuse
- **Data:** pipelines, SQL analytics, datasets for the BI team, KPI reporting
- **Backend and integrations:** Python services and microservices, APIs, AWS (Lambda, S3, EventBridge, API Gateway, Bedrock)
- **Delivery:** automated tests, continuous integration, reproducible environments, documentation

## Featured project

### [series-ar-qlora](https://github.com/estanimolinas/series-ar-qlora)

An agent that answers questions about official Argentine time series by querying the datos.gob.ar API with three tools. The project fine-tunes a small language model (Qwen3-4B, 4-bit) with QLoRA and compares it with the same model without fine-tuning.

<img src="assets/resultado.svg" alt="Test accuracy: 28.4% for the base model with an optimized prompt versus 72.8% for the QLoRA model, on 585 questions from 23 held-out dataset families" width="100%">

- **Evaluation design:** family-based split to prevent leakage between training and test, a custom evaluator validated with an oracle agent and negative controls, test set evaluated once per model.
- **Engineering:** 128 tests, continuous integration with GitHub Actions, reproducible environment with `uv`, documented API costs.
- **Documented limitations** in the README: one training seed, asymmetric prompts between models, questions generated with a language model.

## Experience

- **Junior AI & Data Engineer — Colonia Suiza** (Jul 2026–present). Innovation Team, IT Department. Hybrid role between AI engineering, data engineering and product thinking. AI agents and their harnesses, RAG systems and knowledge bases, and data pipelines for the BI team, across 4 business verticals in claims management. Success metrics (time per task, adoption, repeat use) defined before building and tracked from the first release.

**Previous roles**

- **Instructor — Diplomacia Activa** (2026, remote). Workshop "AI Tools for Political Scientists and International Relations Professionals": LLMs (Claude) and NotebookLM applied to Political Science and Social Sciences.
- **AI Product Manager — Project Copilot LLC** (2026, US, remote). Sprint kickoffs, backlog prioritization, Scrum facilitation. Sprint audits and epic and user story drafting with Claude and the Atlassian MCP (Rovo) against the GitHub repository.
- **B2G Consultant — ASSAL** (Oct 2025–Jul 2026, Santa Fe Province Ministry of Health). Food Handling Certification course digitalized from scratch (1,000+ users on Moodle) and roadmap for 15 educational videos.
- **AI-Driven Operations Manager — Zagged** (Mar–May 2026, NYC, remote). 35+ concurrent international campaigns with a 30% reduction in delivery time. Reporting automated with Notion Agents and a Claude Skill.md.
- **Junior SEO Analyst — Refindable** (Jan–Sep 2025, US, remote). SEO performance and content for clients in the US and Australia. Google Search Console → Looker Studio integration for KPI reporting. QA testing of a pre-trained LLM for article writing.
- **AI Product Manager Trainee — Project Copilot** (Apr 2024–Jan 2025, Santa Fe, remote). Full product cycle (discovery → delivery) with the CTO and PM, using Scrum and Kanban. SOPs documented to standardize team workflows.

## Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

- **Stack:** Python · SQL · AWS (Lambda, S3, EventBridge, API Gateway, Bedrock) · LLM APIs · Langfuse
- **Product background:** backlog and roadmap · discovery → delivery · A/B testing · stakeholder management
- **Methodologies:** Scrum · Agile · Kanban
- **Currently learning:** Flask · Claude Agent SDK · product analytics tools (Google Analytics, Amplitude, Mixpanel)

## Education

- Specialization and Master's in Data Mining — UTN Santa Fe (2026–2029, in progress)
- Bachelor's in International Relations — UCSF (2022–2026), GPA 9.31/10. Thesis (grade: 10): "The Development of Artificial Intelligence in Cyberspace: US-China Bilateral Relations, 2017-2025"
- Exchange semester in Global Law and Transnational Studies — Università degli Studi di Torino (2023–2024)
- Business Track / AI Agency — Golem Lab AI (2026, in progress)
- Empower Digital Product Leaders™ — ITtude, intensive Product Management mentorship (Apr–Jul 2026)

## Certifications

Registered Product Owner™ (RPO) and Registered Scrum Master™ (RSM) — Scrum Inc. · Google Project Management Professional — Coursera (Jan 2025) · Product Manager Flex — Coderhouse · Claude Code in Action — Anthropic · How Transformer LLMs Work — DeepLearning.AI · EF SET English Certificate — C1 Advanced

---

## Español

Junior AI & Data Engineer en gerencia de siniestros. El rol combina ingeniería de IA, ingeniería de datos y mirada de producto: agentes LLM y sus harnesses (herramientas, contexto y evaluación), sistemas RAG y bases de conocimiento, y pipelines de datos que ponen información confiable a disposición del equipo de BI. Cada solución se lleva de punta a punta, desde entender el problema hasta entregarla y medir el resultado. Los roles previos en product management, analítica de datos y consultoría para el sector público dan forma a cómo se define, prioriza y mide el alcance.

## Alcance del trabajo

- **IA:** agentes LLM y harnesses (uso de herramientas, contexto, evaluación), RAG y bases de conocimiento, ajuste con QLoRA, observabilidad de agentes con Langfuse
- **Datos:** pipelines, analítica con SQL, datasets para el equipo de BI, reporting de KPIs
- **Backend e integraciones:** servicios y microservicios en Python, APIs, AWS (Lambda, S3, EventBridge, API Gateway, Bedrock)
- **Entrega:** tests automatizados, integración continua, entornos reproducibles, documentación

## Proyecto destacado

### [series-ar-qlora](https://github.com/estanimolinas/series-ar-qlora)

Agente que responde preguntas sobre series de tiempo oficiales de Argentina consultando la API de datos.gob.ar con tres herramientas. El proyecto ajusta con QLoRA un modelo de lenguaje de tamaño reducido (Qwen3-4B, 4 bits) y lo compara con el mismo modelo sin ajustar.

<img src="assets/resultado.svg" alt="Exactitud en test: 28,4 % del modelo base con prompt optimizado frente a 72,8 % del modelo con QLoRA, sobre 585 preguntas de 23 familias de datasets reservadas" width="100%">

- **Diseño de la evaluación:** partición por familias para evitar fuga entre entrenamiento y prueba, evaluador propio validado con un agente oráculo y controles negativos, test evaluado una sola vez por modelo.
- **Ingeniería:** 128 tests, integración continua con GitHub Actions, entorno reproducible con `uv`, costos de la API documentados.
- **Limitaciones documentadas** en el README: una semilla de entrenamiento, prompts asimétricos entre modelos y preguntas generadas con un modelo de lenguaje.

## Experiencia

- **Junior AI & Data Engineer — Colonia Suiza** (jul. 2026–actualidad). Equipo de Innovación, Departamento IT. Rol híbrido entre ingeniería de IA, ingeniería de datos y mirada de producto. Agentes de IA y sus harnesses, sistemas RAG y bases de conocimiento, y pipelines de datos para el equipo de BI, en 4 verticales de negocio de gerencia de siniestros. Métricas de éxito (tiempo por tarea, adopción, uso recurrente) definidas antes de construir y seguidas desde la primera versión.

**Roles anteriores**

- **Profesor — Diplomacia Activa** (2026, remoto). Taller "Herramientas de IA para politólogos e internacionalistas": LLMs (Claude) y NotebookLM aplicados a Ciencia Política y Ciencias Sociales.
- **AI Product Manager — Project Copilot LLC** (2026, US, remoto). Sprint kickoffs, priorización de backlog, facilitación Scrum. Auditoría de sprints y redacción de epics e historias de usuario con Claude y el MCP de Atlassian (Rovo) sobre el repositorio de GitHub.
- **Consultor B2G — ASSAL** (oct. 2025–jul. 2026, Ministerio de Salud de Santa Fe). Digitalización desde cero del curso de Certificación en Manipulación de Alimentos (+1.000 usuarios en Moodle) y roadmap de 15 videos educativos.
- **AI-Driven Operations Manager — Zagged** (mar.–may. 2026, NYC, remoto). 35+ campañas internacionales concurrentes con una reducción del 30 % en el tiempo de entrega. Reporting automatizado con Notion Agents y un Claude Skill.md.
- **Junior SEO Analyst — Refindable** (ene.–sept. 2025, US, remoto). SEO performance y contenido para clientes de USA y Australia. Integración Google Search Console → Looker Studio para reporting de KPIs. QA de un LLM preentrenado para redacción de artículos.
- **AI Product Manager Trainee — Project Copilot** (abr. 2024–ene. 2025, Santa Fe, remoto). Ciclo completo de producto (discovery → delivery) junto al CTO y el PM, con Scrum y Kanban. SOPs documentados para estandarizar los workflows del equipo.

## Habilidades

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)

- **Stack:** Python · SQL · AWS (Lambda, S3, EventBridge, API Gateway, Bedrock) · APIs de LLM · Langfuse
- **Trayectoria en producto:** backlog y roadmap · discovery → delivery · A/B testing · gestión de stakeholders
- **Metodologías:** Scrum · Agile · Kanban
- **En desarrollo:** Flask · Claude Agent SDK · herramientas de analítica de producto (Google Analytics, Amplitude, Mixpanel)

## Educación

- Especialización y Maestría en Minería de Datos — UTN Regional Santa Fe (2026–2029, en curso)
- Licenciatura en Relaciones Internacionales — UCSF (2022–2026), promedio 9,31. Tesis (10): "El Desarrollo de la Inteligencia Artificial en el Ciberespacio: La Relación Bilateral de los Estados Unidos y China entre 2017-2025"
- Intercambio en Global Law and Transnational Studies — Università degli Studi di Torino (2023–2024)
- Track de Negocios / AI Agency — Golem Lab AI (2026, en curso)
- Empower Digital Product Leaders™ — ITtude, mentoría intensiva de Product Management (abr.–jul. 2026)

## Certificaciones

Registered Product Owner™ (RPO) y Registered Scrum Master™ (RSM) — Scrum Inc. · Google Project Management Professional — Coursera (ene. 2025) · Product Manager Flex — Coderhouse · Claude Code in Action — Anthropic · How Transformer LLMs Work — DeepLearning.AI · EF SET English Certificate — C1 Advanced
