# Customer Attrition Model — Release Audit Log

Append-only record of candidate evaluations against `governance/release_policy.json`.

| Date | Run | Steps | Final val_auc | AUC std (last 50) | Improvement vs champion | Decision |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-05-20 | cand_wide_emb_q3_2026 | 480 | 0.8452 | 0.0071 | 0.0102 | HOLD |
| 2026-06-30 | cand_early_stop_q3_2026 | 480 | 0.8291 | 0.0034 | -0.0059 | HOLD |
| 2026-07-15 | baseline_q3_2026 | 480 | 0.8350 | 0.0019 | 0.0000 | CHAMPION |
