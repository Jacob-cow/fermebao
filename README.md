# FermeBao — Herd Management

Application de gestion du troupeau FermeBao :
- Gestion des vaches (fiche, statut)
- Reproduction (chaleurs, insémination, diagnostic gestation, vêlage)
- Lactation (production journalière)
- Veaux (naissances, pesées, croissance)

## MVP (V1)
- CRUD Vaches
- Événements Reproduction (HEAT, AI, PREG_CHECK, CALVING)
- Production laitière par jour
- Veaux + pesées
- API documentée via Swagger (OpenAPI)

## Tech
- Java 21 + Spring Boot 3
- PostgreSQL
- Docker Compose

## Lancer en local (Docker)
1) Démarrer la DB :
```bash
docker compose up -d db
