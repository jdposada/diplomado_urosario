# Diplomado en Salud Digital y Ciencia de Datos en Salud — Universidad del Rosario

## Taller Práctico de OMOP Common Data Model (CDM) con Python y OHDSI Eunomia

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jdposada/diplomado_urosario/blob/main/eunomia_omop_showcase_es.ipynb)

Este repositorio contiene el material práctico e interactivo para la sesión sobre el **Modelo Común de Datos OMOP (OMOP CDM v5.4)** y los **Vocabularios Estandarizados de OHDSI**.

---

### Contenido del Cuaderno
1. **Configuración y Carga de Datos**: Ingestión automatizada del dataset sintético **OHDSI Eunomia** en **DuckDB**.
2. **Recorrido por el Modelo OMOP CDM**: Arquitectura centrada en el paciente (`PERSON`, `OBSERVATION_PERIOD`, `VISIT_OCCURRENCE`, `CONDITION_OCCURRENCE`, `DRUG_EXPOSURE`, `MEASUREMENT`).
3. **Motor de Vocabularios Estandarizados**: Mapeo de códigos fuente a conceptos estándar (`'Maps to'`) mediante `CONCEPT_RELATIONSHIP`.
4. **Pipeline ETL en 3 Fases**: Transformación paso a paso de historias clínicas crudas hacia tablas estándar (`Prepped` -> `Mapped` -> `Keyed`) con validación de esquemas oficiales con `pyomop`.
5. **Definición de Cohortes y Analítica Clínica**: Extracción SQL de cohortes incidentes y análisis de medicación concomitante con gráficos interactivos.
6. **Ejercicios Prácticos del Diplomado**:
   - **Ejercicio 1**: Identificación visual del evento índice y evaluación del período de observación previa continua (Líneas de tiempo comparativas entre Paciente A y Paciente B).
   - **Ejercicio 2**: Mapeo de códigos fuente y enrutamiento por dominio (*Domain Routing*) en `CONCEPT_RELATIONSHIP`.
   - **Ejercicio 3**: Farmacovigilancia y detección de fármacos concomitantes (AINEs) previos al evento índice.

---

### Ejecución Directa en Google Colab
Puede abrir directamente el cuaderno interactivo haciendo clic en la insignia:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jdposada/diplomado_urosario/blob/main/eunomia_omop_showcase_es.ipynb)
