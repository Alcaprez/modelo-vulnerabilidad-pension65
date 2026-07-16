# Modelo predictivo de vulnerabilidad social — Usuarios de Pensión 65

Proyecto del curso Cómputo Distribuido y Paralelo (UPAO).
Análisis comparativo entre La Libertad y el territorio nacional.

## Datasets
- `nivel_micro.csv`: 33,691 hogares con variables de ENAHO 2024 (pobreza, NBI, salud, composición del hogar).
- `nivel_macro_final_completo.csv`: 25 regiones, con cobertura de Pensión 65 (ENAHO y padrón administrativo) e índice de vulnerabilidad CEPLAN.

## Fuentes originales
- INEI - Encuesta Nacional de Hogares (ENAHO) 2024
- MIDIS - Padrón de beneficiarios de Pensión 65
- CEPLAN - Sub-índices de vulnerabilidad territorial 2013-2024

## Notebook
`Modelo de clasificación: vulnerable/ no vulnerable.ipynb` — pipeline completo: carga de datos, construcción del índice de vulnerabilidad (Alkire-Foster), entrenamiento y comparación de modelos (Regresión Logística vs. Random Forest), cómputo paralelo y análisis territorial.
