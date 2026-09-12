# Development log

## 2026-09-13 - Reconcile published source into main

The default branch now includes the published v0.1.2 source. The release workflow uses the existing PSX-PUB-031 indentation repair. Later catalog identities and the current recomp-ui repository URL are preserved. The pinned runtime and UI commits match v0.1.2. No new package, release, gameplay test, or source-pin promotion is claimed.

Corpus consulted: PSX-PUB-031 and FAIL-142. The existing audit_release_workflow.py parser and regression supply the repair. Primary reference: https://github.com/softprops/action-gh-release documents overwrite_files under with. Source checks cover YAML structure, Actionlint, title executable-name tests when present, manifest versions, and exact release gitlinks.
