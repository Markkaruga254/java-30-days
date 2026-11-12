# Capstone: Secure Expense or Library API

Turn your Day 14 project into a production-style service. You may use a different domain if it has authentication, persistence and at least four related entities.

## Requirements checklist

- [ ] Spring Boot REST API with JPA and PostgreSQL
- [ ] JWT authentication and role-based access
- [ ] Bean Validation, consistent JSON error handling, structured logging
- [ ] Unit and integration tests
- [ ] CI pipeline on GitHub Actions (see `ci.yml.template`)
- [ ] Dockerfile and `docker compose` setup
- [ ] README with architecture diagram, setup steps and API examples
- [ ] "Security decisions" section explaining password hashing, token handling, access checks, and one vulnerability you found and fixed

## Final deliverables (Day 30)

- [ ] Tag `v1.0`
- [ ] 3 to 5 minute demo (screen recording or GIF)
- [ ] Retrospective in `weekly-reviews/week-4.md`

## Suggested layout

```
capstone/
├── pom.xml (or build.gradle)
├── Dockerfile
├── docker-compose.yml
├── src/main/java/...
├── src/test/java/...
└── README.md
```
