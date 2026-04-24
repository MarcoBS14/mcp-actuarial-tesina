# MCP Actuarial — Notebook de apoyo

Notebook ejecutable que reproduce los resultados cuantitativos reportados 
en la tesina:

**Barragán Sosa, M. A. (2026).** *MCP Actuarial: un marco de documentación 
y gobernanza para modelos GLM en seguros.* Tesina de Licenciatura en 
Actuaría, Universidad Anáhuac Veracruz.

## Contenido

- `MCP_v3.ipynb` — Notebook completo con las 9 secciones del MCP 
  aplicadas al conjunto freMTPL2freq.

## Reproducibilidad

- Python 3.10+
- Paquetes: pandas, numpy, statsmodels, scikit-learn, matplotlib, shap
- Semilla fija: random_state = 42
- Dataset: freMTPL2freq (paquete CASdatasets de R, versión 1.2-0, 
  DOI 10.57745/P0KHAG)
