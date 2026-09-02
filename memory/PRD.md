
## 2026-06 Deployment readiness
- Seed made idempotent (no delete_many at startup); logo URL moved to REACT_APP_LOGO_URL; .env removed from .gitignore.
- Deployment health check: PASS (no blockers). Remaining WARN: /api/racks and /api/dashboard/trends use looped count queries (small dataset, acceptable).
- Static HTML build zip at /app/spms_html_build.zip.
