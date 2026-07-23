# Acta

.NET solution following a layered architecture (Domain, Application, Infrastructure, Api).

## Structure

- `src/Acta.Domain` — domain entities (Cases, Hearings, Residents, Users, Documents, Auditing)
- `src/Acta.Application` — application logic
- `src/Acta.Infrastructure` — infrastructure implementations
- `src/Acta.Api` — API host
- `tests/` — unit, integration, and architecture tests

## Requirements

- .NET SDK 10.0.100 (see `global.json`)

## Getting started

```
dotnet build
dotnet test
dotnet run --project src/Acta.Api
```
