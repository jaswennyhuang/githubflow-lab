# githubflow-lab (platform repo, Lab 2: GitHub Flow)

Only `main`. Each folder is one environment.

- `environments/dev/`: written by a service on every merge → deploys **dev**
- `environments/staging/`: written by a service on every release tag → deploys **staging**
- `environments/prod/`: changed only through a **promote PR** (one service at a time) → deploys **prod** after approval
- `promote`: run by hand. Empty version = what staging runs. An old tag = rollback.
