# Arcadia · Pipeline Snapshot

Dashboard minimalista para visualizar el pipeline de discovery calls de Arcadia. HTML + CSS + JS vanilla, sin build, sin dependencias.

## Correr localmente

```bash
python3 -m http.server 8000
```

Luego abrir http://localhost:8000

## Agregar un lead

Editar `data.json`:

```json
{
  "name": "Nombre Apellido",
  "ig": "@handle",
  "tier": "Mastermind",
  "low": 10000,
  "high": 25000,
  "niche": "Trading"
}
```

`tier` debe ser: `Mastermind`, `Consultoria`, `Consulting`, o `VSL Funnel`.
