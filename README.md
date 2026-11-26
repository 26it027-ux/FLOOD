# Flood Intelligence

A software-only urban flood nowcasting prototype for Chennai's T. Nagar pilot ward.

The project provides a street-level flood-risk interface with:

- illustrative flood-risk map markers
- modeled rainfall and drainage data
- safer-route and forecast concepts
- explainable segment risk information
- stale-data simulation controls

## Run locally

From this repository folder:

```powershell
python -m http.server 8000
```

Then open http://127.0.0.1:8000/flood-intelligence.html.

## Data notice

All values, rainfall, freshness times, geometry, and validation figures are illustrative sample data. This prototype is not connected to municipal or emergency warning systems and is not suitable for real-world navigation or emergency decisions.
