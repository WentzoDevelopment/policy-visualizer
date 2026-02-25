# Policy Visualizer Release Notes Template

> Copy this file for each release (for example: `docs/releases/2.0.0-alpha.1.md`) and fill in each section.

## Release

- Version: `X.Y.Z[-pre.N]`
- Release date: `YYYY-MM-DD`
- Release type: `alpha | beta | rc | ga | patch`
- Commit/tag: ``

## Summary

Short overview of what this release delivers and why it matters.

## Highlights

- 
- 
- 

## Scope for This Release

- Included:
  - 
- Not included:
  - 

## Breaking Changes

- None

If there are breaking changes, list each one with migration guidance:
- Change:
- Impact:
- Action required:

## Features

### Export
- 

### Diagram UX
- 

### Policy/Compiler Pipeline
- 

### API
- 

## Fixes

- 
- 
- 

## Tests and Validation

- Test command(s):
  - `pytest`
  - `pytest tests/test_api_routes.py tests/test_flow_ir.py`
- Result summary:
  - 
- Determinism checks:
  - 

## Known Issues

- 
- 

## Upgrade Notes

- Docker:
  - `docker compose up --build`
- API/Frontend version alignment checks:
  - `api/main.py`
  - `frontend/package.json`

## Ticket Coverage

List completed tickets from the release map/backlog:
- REL-
- EXP-
- ANN-
- UX-
- COL-
- ISE- (discovery/spec only for 2.0.0)

## Deferred / Next Milestone

Items intentionally deferred to next release:
- 

Planned next target:
- `X.Y.Z`

## Artifact Checklist

- [ ] Release notes finalized
- [ ] Version updated in backend metadata (`api/main.py`)
- [ ] Version updated in frontend package (`frontend/package.json`)
- [ ] Changelog entry added (if maintained separately)
- [ ] Tag created
- [ ] Docker build verified
- [ ] Tests passing

---

## Optional Appendix: ISE Discovery Status (2.0 Track)

Use this section during 2.0 pre-releases to track Cisco ISE discovery/spec progress.

- Mapping matrix status:
- Fixture plan status:
- Open questions/risks:
- Recommendation for 2.1.0 import implementation:
