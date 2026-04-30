# Retail Marketing Governance Case

Caso de marketing engineering sobre retencion post-prueba de un nuevo producto retail. El objetivo es maximizar margen neto retenido combinando gobernanza tabular, auditoria detectivesca, baseline parsimonioso, CLV probabilistico y activacion tactica con Next Best Action.

## Estructura

- `conf/settings.yaml`: contrato externo del caso con meta de negocio, target, roles tabulares, reglas de muestreo, CLV y activacion.
- `data/raw/retail_product_marketing_synthetic.csv`: dataset sintetico del cohort post-trial.
- `data/processed/`: scorecards y umbrales exportados por el notebook.
- `notebooks/retail_marketing_governance_case.ipynb`: notebook maestro del proyecto.

## Entregable metodologico

El notebook sigue cinco fases:

1. Planteamiento estrategico.
2. Gobernanza y contrato tabular.
3. Auditoria detectivesca: faltantes, outliers, normalidad y multicolinealidad.
4. Modelado parsimonioso con baseline interpretable.
5. Capa de marketing engineering: CLV, threshold economico y scorecard NBA.

## Ejecucion

Usa el entorno Python 3.11 del workspace. Abre el notebook y ejecútalo de arriba abajo para regenerar salidas en `data/processed/`.
