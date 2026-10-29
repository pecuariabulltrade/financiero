# Sitio del Portal Financiero (GitHub Pages)

Estático: `index.html` + `config.js` + `planilla.json`. Lee Supabase (proyecto «financiero») con la anon key y login de Supabase.
- Dashboard: últimas publicaciones por empresa (`financiero_publicado`), con día a día y gráficos.
- Saldos de la mañana (solo operadora/admin): misma planilla que el portal local, guarda en `saldos_diarios`.
Publicar: copiar esta carpeta a la raíz del repo (o a `docs/`) y activar GitHub Pages.
Si se cambia `PLANILLA_SALDOS` en `financiero.py`, regenerar `planilla.json`.
