# Big Brother — Triage Aumentado con IA

Demo que compara análisis superficial vs análisis profundo detectando casos mal clasificados.

**Stack**: Python 3.12 · pandas · Faker · openai (NVIDIA NIM)

**Datos**: 50 registros sintéticos, 18 con discrepancia entre score aparente y real.

### Cómo usar

```bash
uv run jupyter notebook notebooks/01_analisis_triage.ipynb
```

Para generar datos frescos: `uv run python scripts/generar_datos.py`
