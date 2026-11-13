# churn-predictor

Customer attrition model for the retail banking portfolio. Training runs are
tracked in the team's experiment tracking workspace; release candidates are
evaluated at the end of every quarter.

## Release governance

- `governance/release_policy.json` — single source of truth for the release gate thresholds.
- `governance/audit_log.md` — append-only audit log; every evaluated candidate gets one row.

The audit log is updated by the release manager after each gate review.
