# Catálogo de proyectos

Este catálogo organiza los repositorios desarrollados para el portfolio. Todos incluyen licencia MIT, pruebas automatizadas y una definición explícita de alcance; son proyectos de referencia y aprendizaje, no afirmaciones de despliegues productivos.

## Plataforma FactoryPulse

| Componente | Función |
| --- | --- |
| [Contracts](https://github.com/david2526IA/factorypulse-contracts) | Esquemas versionados para telemetría, anomalías e indicadores de calidad. |
| [Ingestion](https://github.com/david2526IA/factorypulse-ingestion) | Simula y valida telemetría industrial. |
| [Lakehouse](https://github.com/david2526IA/factorypulse-lakehouse) | Construye capas bronze/silver/gold con DuckDB y Parquet. |
| [Intelligence](https://github.com/david2526IA/factorypulse-intelligence) | Detecta anomalías con motivos comprensibles. |
| [API](https://github.com/david2526IA/factorypulse-api) | Expone resultados de forma estrictamente de solo lectura. |
| [Dashboard](https://github.com/david2526IA/factorypulse-dashboard) | Visualiza el estado operativo y el linaje de datos. |
| [Notifier](https://github.com/david2526IA/factorypulse-notifier) | Convierte eventos validados en alertas deduplicadas para revisión. |
| [Maintenance Planner](https://github.com/david2526IA/factorypulse-maintenance-planner) | Propone acciones de mantenimiento que requieren aprobación humana. |
| [Reporting](https://github.com/david2526IA/factorypulse-reporting) | Genera informes HTML portátiles basados en evidencias. |
| [Orchestrator](https://github.com/david2526IA/factorypulse-orchestrator) | Ejecuta el flujo completo con versiones fijadas. |

## IA, RAG y visión

| Proyecto | Función |
| --- | --- |
| [LocalDocs](https://github.com/david2526IA/localdocs) | Recuperación documental local con fuentes visibles. |
| [RAG Eval Lite](https://github.com/david2526IA/rag-eval-lite) | Métricas de recuperación Recall@k y MRR@k. |
| [Prompt Hygiene](https://github.com/david2526IA/prompt-hygiene) | Revisión local de posibles datos sensibles antes de usar IA. |
| [VisionInspect](https://github.com/david2526IA/visioninspect) | Línea base de inspección visual explicable. |
| [Label Agreement](https://github.com/david2526IA/label-agreement) | Control de acuerdo entre anotadores de un dataset. |
| [ML Drift Watch](https://github.com/david2526IA/ml-drift-watch) | Señal PSI para comparar distribuciones de datos. |

## Robótica, automatización y Edge

| Proyecto | Función |
| --- | --- |
| [PredictivePlant](https://github.com/david2526IA/predictiveplant) | Detección explicable de comportamiento anómalo en telemetría. |
| [Robot Trajectory Guard](https://github.com/david2526IA/robot-trajectory-guard) | Revisión offline de límites articulares y cinemáticos. |
| [Workcell Layout Checker](https://github.com/david2526IA/workcell-layout-checker) | Revisión geométrica 2D de separaciones en una célula. |
| [Sensor Calibration Kit](https://github.com/david2526IA/sensor-calibration-kit) | Ajuste lineal y análisis de residuos de sensores. |
| [Edge Telemetry Buffer](https://github.com/david2526IA/edge-telemetry-buffer) | Cola persistente para telemetría sin conexión. |

## Datos, operaciones y herramientas locales

| Proyecto | Función |
| --- | --- |
| [DataLakehouse](https://github.com/david2526IA/datalakehouse) | Pipeline analítico bronze/silver/gold reproducible. |
| [Dataset Quality Gate](https://github.com/david2526IA/dataset-quality-gate) | Validación CSV con aceptados, rechazados y razones. |
| [Log Incident Radar](https://github.com/david2526IA/log-incident-radar) | Detección de picos de error en logs estructurados. |
| [HomePulse](https://github.com/david2526IA/homepulse) | Análisis de consumo energético doméstico. |
| [CityPulse](https://github.com/david2526IA/citypulse) | Consulta local de meteorología y calidad del aire. |
| [File Space Audit](https://github.com/david2526IA/file-space-audit) | Inventario de disco y duplicados exactos, sin borrar ficheros. |
