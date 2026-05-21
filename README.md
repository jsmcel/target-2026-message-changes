# R2026 JUN to NOV Effective Message Changes

This repository publishes a static, self-contained report for the TARGET Services R2026 JUN to NOV message comparison.

## Effective-release rule

The NOV publication set is treated as an update layer. If a message exists in JUN and no newer NOV package is published for the same service and usage-guideline variant, the JUN package is carried forward and remains the effective version.

## Published files

- `index.html`: interactive report.
- `effective_message_changes.csv`: row-level effective matrix.
- `version_changes_consolidated.csv`: consolidated ISO base version changes.

No schema packages, archive files, local corpus data, or private material are published here.
