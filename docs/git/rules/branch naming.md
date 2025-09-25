
## Branch Types

| Type     | Purpose (What it’s for)                  | Example branch name                          | Use when…                                  |
|----------|------------------------------------------|----------------------------------------------|--------------------------------------------|
| `feat`   | New feature / capability                  | `feat/SOF-231-onboarding-overlay`            | You add user-visible functionality         |
| `fix`    | Bug fix (non-urgent)                      | `fix/SOF-198-crash-on-f1`                    | You resolve a reported defect              |
| `hotfix` | Urgent production fix                     | `hotfix/release-startup-regression`          | You must patch prod ASAP                   |
| `refactor` | Internal code change (no behavior change) | `refactor/uia-service-aliases`               | You clean structure/tech debt              |
| `docs`   | Documentation only                        | `docs/readme-badges`                         | You update README, guides, ADRs            |
| `chore`  | Maintenance / tooling / deps              | `chore/upgrade-dotnet-8`                     | You change CI, configs, deps, scripts      |
| `perf`   | Performance improvement                   | `perf/overlay-rendering-throttle`            | You make something faster/more efficient   |
| `test`   | Tests only                                | `test/f1highlighter-e2e`                     | You add/improve tests                      |
| `ci`     | Continuous Integration / pipelines        | `ci/cache-nuget-and-binlog`                  | You tweak workflows/build pipelines        |

**Format:**  
`<type>/<ticket>-<slug>` → e.g., `feat/SOF-231-onboarding-overlay`
