# CLI de citações

Ferramenta de linha de comando que imprime uma citação aleatória ou por índice.

## Overview
- Application: `cli-de-cita-es-f04894`
- Primary language: `csharp`
- Goal: deliver a production-minded backend increment with clear operational behavior.

## Architecture
- Layered organization (entrypoint, domain/application logic, integrations).
- Commit-by-commit incremental evolution to preserve stability.
- Validation gate after every relevant change.

## Project Structure
- `src/` core implementation
- `tests/` automated validations
- `docs/` design notes and evolution logs (when present)

## Setup
1. Install runtime/toolchain for the project language.
2. Install dependencies for the project.
3. Run validation before publishing changes.

## How to Run
```bash
dotnet build <project>.csproj -v q
dotnet run --project <project>.csproj
```

## API / Endpoints
- If this project exposes HTTP endpoints, document contract, status codes and payloads here.
- For CLI/worker projects, document command flags and expected outputs.

## Validation & Tests
- Build and tests must pass before publish.
- Validation failures must be fixed before introducing new scope.

## Observability
- Use structured logs for critical flow points.
- Keep failure messages actionable and concise.

## Limitations
- Initial scaffold may not contain all production hardening.
- Follow-up iterations should improve reliability, security and maintainability.

## Next Steps
- Expand business behavior while preserving test coverage.
- Improve resilience (timeouts/retries) and operational readiness.
