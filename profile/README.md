# embedded-alerts-test

Independent acceptance organization for **embedded-alerts**.

Readiness-gated SDK, API, Flutter/web UI, push-provider, offline queue, and embedded-host certification.

## Portfolio

| Repository | Class | Readiness | Primary dependency path |
|---|---|---|---|
| `eal-clients-consumer-matrix` | SDK consumer | `planned_dependency` | `matrix` |
| `api-contract` | API contract | `planned_dependency` | `matrix` |
| `flutter-ui-e2e` | mobile/emulator | `planned_dependency` | `matrix` |
| `web-ui-e2e` | browser E2E | `planned_dependency` | `matrix` |
| `push-provider-integration` | provider adapter | `planned_dependency` | `matrix` |
| `offline-queue-replay` | synchronization | `planned_dependency` | `matrix` |
| `embedded-widget-hosts` | interoperability | `planned_dependency` | `matrix` |

Pull requests run deterministic harness checks. Emulators, desktop matrices, live APIs/providers, databases, chaos, scale, and soaks are scheduled/manual. Missing upstreams or credentials are blocked readiness—not false passes or product regressions.

<!-- org-project-routing:start -->
## Planning and delivery

- [GitHub Project: embedded-alerts-test-project](https://github.com/orgs/embedded-alerts-test/projects/1)
- [Linear planning project](https://linear.app/denman/project/githubcomembedded-alerts-test-836aab58cf3e)
- [Detailed project-routing contract](../docs/PROJECTS.md)

GitHub owns code and delivery evidence; Linear owns planning and dependencies. The linked organization Project provides the cross-repository execution view.
<!-- org-project-routing:end -->


<!-- ore-org-baseline:begin -->
## Planning and governance

- Canonical Linear project: https://linear.app/denman/project/githubcomembedded-alerts-test-836aab58cf3e
- Organization defaults: https://github.com/embedded-alerts-test/.github
- Canonical agent policy: https://github.com/embedded-alerts-test/.github/blob/main/agents.md
- Security policy: https://github.com/embedded-alerts-test/.github/security/policy

Repositories in this organization use semantic conflict resolution with 3–10 relevant prior commits when useful, full cross-repository context, pull-request delivery, and a hard automated-agent denylist for destructive or history-rewriting operations.
<!-- ore-org-baseline:end -->
