# module-crew-manager

HARNESS module: Crew management — member tracking, certifications, license monitoring.

## Entity Contract

- **Produces:** crew-member
- **Consumes:** none

## Tools

- `add-member` — Add a new crew member
- `update-certifications` — Update a crew member's certifications and licenses
- `check-licenses` — Check for expiring licenses across all crew members

## Validation

```bash
harness module validate .
```
