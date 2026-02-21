# agent-observability-stack

Observability foundation for tracing, metrics, and cost telemetry in agent systems.

## Scope

Trace spans, event logs, token accounting, and SLO dashboards.

## Capabilities

- Trace spans, event logs, token accounting, and SLO dashboards.
- OpenTelemetry-compatible pipeline and cardinality-safe metrics.
- Correlated execution logs with tool and prompt attribution.
- Budget, latency, and error-budget monitoring with alerts.

## Repository Layout

- `src/main.py` entrypoint and lightweight service bootstrap
- `src/project_profile.py` canonical project metadata
- `src/service_contract.py` baseline domain contract shape
- `tests/` smoke and contract tests
- `docs/` architecture and roadmap

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest -q
python -m src.main
```
