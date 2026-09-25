# learn-ml

## Create data

```bash
cd datagen
env -u OPENAI_API_KEY uv run python datagen.py \
  --plan ../data/plans/car_fuel_efficiency_2026_plan.json \
  --accept \
  --outdir ../data
```