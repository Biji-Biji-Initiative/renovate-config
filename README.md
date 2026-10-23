# renovate-config

Shared Renovate preset for Biji-Biji-Initiative. Public on purpose (it holds no secrets) so any repo-scoped token can resolve it.

Onboard a repo: commit `renovate.json` with

```json
{ "extends": ["github>Biji-Biji-Initiative/renovate-config"] }
```

Opt in to automerge of patch devDependencies (only where CI gates the PR):

```json
{ "extends": ["github>Biji-Biji-Initiative/renovate-config", "github>Biji-Biji-Initiative/renovate-config:automerge-dev-patch"] }
```

Runner, schedule, credential and rollback: team-skills `tools/renovate/README.md`.
