# Catálogo de proyectos

Este catálogo ordena los repositorios por especialidad técnica. Los proyectos propios se muestran primero; los forks y laboratorios de aprendizaje quedan separados para que la autoría sea transparente.

## 1. Investigación en robótica física

Prototipos para interacción humano-robot, teleoperación, simulación y robótica abierta.

| Proyecto | Tecnologías / enfoque |
| --- | --- |
| [Astro Reachy](https://github.com/david2526IA/astro-reachy) | Experiencia educativa del Sistema Solar para **Reachy Mini**. |
| [OpenArm · Isaac Lab · RL](https://github.com/david2526IA/openarm-isaac-rl-teleop) | **Reinforcement learning**, teleoperación VR, visión simulada y NVIDIA Isaac Lab. |
| [School Menu Assistant](https://github.com/david2526IA/school-menu-assistant) | Asistente de voz para Reachy Mini con reglas verificables y modelos locales. |
| 🔒 Reachy Mini Lite Eldercare | Asistente multimodal local para asistencia: voz, visión, puente de robot y flujos de entrenamiento. |
| [XLERobot Digital Twin](https://github.com/david2526IA/xlerobot-digital-twin) | Gemelo digital orientado a experimentación robótica. |
| [Robo Platform](https://github.com/david2526IA/robo-platform) | Base de exploración para una plataforma robótica. |
| [Robot Trajectory Guard](https://github.com/david2526IA/robot-trajectory-guard) | Validación offline de límites articulares y trayectorias. |
| 🔒 OpenArm ROS 2 Camera Bridge | Puente de cámara robusto para OpenArm: USB, archivo, stream y fuentes sintéticas. |
| 🔒 LeRobot / LeKiwi Field Guide | Instalación, calibración, teleoperación, datasets, entrenamiento y diagnóstico. |
| 🔒 MicroDuck RL | Experimentos privados de aprendizaje por refuerzo. |

## 2. IA aplicada, deep learning y modelos abiertos

Trabajo con LLM, RAG, privacidad, evaluación y flujos reproducibles de IA.

| Proyecto | Tecnologías / enfoque |
| --- | --- |
| [LocalDocs](https://github.com/david2526IA/localdocs) | Búsqueda documental privada, local y basada en fuentes; **RAG** y FastAPI. |
| [RAG Eval Lite](https://github.com/david2526IA/rag-eval-lite) | Evaluación reproducible de recuperación con Recall@k y MRR@k. |
| [Prompt Hygiene](https://github.com/david2526IA/prompt-hygiene) | Revisión local de texto sensible antes de usar herramientas de IA. |
| [ML Drift Watch](https://github.com/david2526IA/ml-drift-watch) | Monitorización explicable de drift de datos mediante PSI. |
| [Label Agreement](https://github.com/david2526IA/label-agreement) | Métricas de acuerdo entre anotadores para datasets de IA. |
| 🔒 LexIA | Asistente jurídico por voz para Reachy Mini, local y trazable. |

## 3. Visión artificial y calidad de datasets

Herramientas para inspección visual, construcción de datasets y trazabilidad de sus etiquetas.

| Proyecto | Tecnologías / enfoque |
| --- | --- |
| [VisionInspect](https://github.com/david2526IA/visioninspect) | Inspección visual explicable de superficies: visión artificial y ML. |
| [ArchaeoSort Dataset Builder](https://github.com/david2526IA/archaeosort-dataset-builder) | Construcción, validación y auditoría reproducible de datasets arqueológicos de visión artificial. |
| [Label Agreement](https://github.com/david2526IA/label-agreement) | Control de calidad de anotaciones; también listado en IA aplicada. |

## 4. Datos, big data y MLOps

Pipelines reproducibles, calidad de datos, lakehouse y observabilidad operativa.

| Proyecto | Tecnologías / enfoque |
| --- | --- |
| [DataLakehouse](https://github.com/david2526IA/datalakehouse) | Pipeline bronze/silver/gold con **DuckDB** y Parquet. |
| [Dataset Quality Gate](https://github.com/david2526IA/dataset-quality-gate) | Validación CSV con esquema, aceptados, rechazados y razones auditables. |
| [Log Incident Radar](https://github.com/david2526IA/log-incident-radar) | Detección local de picos de error en logs JSONL. |
| [Edge Telemetry Buffer](https://github.com/david2526IA/edge-telemetry-buffer) | Cola SQLite persistente para telemetría edge sin conexión. |
| [HomePulse](https://github.com/david2526IA/homepulse) | Analítica local de consumo energético y previsión de demanda. |
| [CityPulse](https://github.com/david2526IA/citypulse) | Meteorología y calidad del aire con datos públicos. |
| [File Space Audit](https://github.com/david2526IA/file-space-audit) | Inventario de disco y detección de duplicados, sin eliminar archivos. |
| 🔒 Comedor Fácil / Txopitea Comedor | Prototipos de asistentes de voz para la gestión del comedor escolar con Reachy Mini. |

## 5. IA industrial, automatización y sistemas ciberfísicos

Esta línea recoge aplicaciones de los mismos principios de datos e IA a sensores, telemetría y automatización. Es una especialidad complementaria, no el eje único del portfolio.

| Proyecto | Tecnologías / enfoque |
| --- | --- |
| [PredictivePlant](https://github.com/david2526IA/predictiveplant) | Detección explicable de anomalías para telemetría. |
| [Sensor Calibration Kit](https://github.com/david2526IA/sensor-calibration-kit) | Calibración lineal y análisis de residuos de sensores. |
| [Workcell Layout Checker](https://github.com/david2526IA/workcell-layout-checker) | Comprobación 2D de separaciones en células robóticas. |

### Plataforma FactoryPulse

Proyecto modular de datos para telemetría: contratos → ingesta → lakehouse → inteligencia → API → visualización y operaciones.

| Componente | Función |
| --- | --- |
| [Contracts](https://github.com/david2526IA/factorypulse-contracts) | Esquemas versionados para telemetría, anomalías e indicadores de calidad. |
| [Ingestion](https://github.com/david2526IA/factorypulse-ingestion) | Simulación y validación de telemetría. |
| [Lakehouse](https://github.com/david2526IA/factorypulse-lakehouse) | Capas bronze/silver/gold con DuckDB y Parquet. |
| [Intelligence](https://github.com/david2526IA/factorypulse-intelligence) | Detección de anomalías con motivos comprensibles. |
| [API](https://github.com/david2526IA/factorypulse-api) | Resultados de solo lectura. |
| [Dashboard](https://github.com/david2526IA/factorypulse-dashboard) | Estado operativo y linaje de datos. |
| [Notifier](https://github.com/david2526IA/factorypulse-notifier) | Alertas trazables y deduplicadas. |
| [Maintenance Planner](https://github.com/david2526IA/factorypulse-maintenance-planner) | Propuestas de mantenimiento con aprobación humana. |
| [Reporting](https://github.com/david2526IA/factorypulse-reporting) | Informes HTML basados en evidencias. |
| [Orchestrator](https://github.com/david2526IA/factorypulse-orchestrator) | Ejecución reproducible del flujo completo. |

## 6. Laboratorios y referencias externas

Estos repositorios son **forks o materiales de práctica**. Se conservan como referencia técnica y no se presentan como desarrollos propios.

| Repositorio | Área |
| --- | --- |
| [ComfyUI](https://github.com/david2526IA/ComfyUI) | Interfaces y flujos para modelos de difusión. |
| [Unsloth](https://github.com/david2526IA/unsloth) | Entrenamiento y ejecución local de modelos abiertos. |
| [OpenArm](https://github.com/david2526IA/openarm) | Brazo humanoide de código abierto para Physical AI. |
| [RAG Llama CPP Starter](https://github.com/david2526IA/rag-llama-cpp-starter) | Laboratorio de RAG dockerizado. |
| [Spark DataFrames Lab](https://github.com/david2526IA/spark-dataframes-lab) | Prácticas de Spark y Big Data. |
| [Kafka Monitoring Lab](https://github.com/david2526IA/kafka-monitoring-lab) | Prácticas de monitorización con Kafka. |
| [Data Integrity HDFS Lab](https://github.com/david2526IA/data-integrity-hdfs-lab) | Integridad de datos en HDFS. |
| [Hadoop Despliegue](https://github.com/david2526IA/Hadoop_despliegue) | Despliegue Docker de Hadoop y consultas HDFS. |
| [Demo Dask 500 GB](https://github.com/david2526IA/demo_dask_500gb-) | Procesamiento de grandes volúmenes y S3. |
| [AWS Academy S3 Streamlit](https://github.com/david2526IA/ra2-awsacademy-s3-streamlit-starter-template) | Práctica de datos y Streamlit. |

Todos los proyectos propios persiguen documentación clara, pruebas automatizadas cuando aplica y límites operativos explícitos. Una demo o herramienta de análisis no se presenta como sistema de control ni certificación de seguridad.
