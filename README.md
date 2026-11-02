# Build a Celestial Bodies Database

FreeCodeCamp Relational Databases v9 certification project (unit 025).

`universe.sql` recreates the `universe` PostgreSQL database (galaxy, star, planet, moon, asteroid)
satisfying the project's user stories. Rebuild with:

```
psql -U postgres < universe.sql
```

Built as a fleet run in timerloggedout-spec/termux-monorepo (`cert-project.yml` run 41378291157):
build.sql applied to PostgreSQL 16, all user stories verified in-run, dump round-trip re-verified.
