# Customer Attrition Model — Release Audit Log

Append-only record of candidate evaluations against `governance/release_policy.json`.

| Date | Run | Steps | Final val_auc | AUC std (last 50) | Improvement vs champion | Decision |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-05-20 | cand_wide_emb_q3_2026 | 480 | 0.8452 | 0.0071 | 0.0102 | HOLD |
| 2026-06-30 | cand_early_stop_q3_2026 | 480 | 0.8291 | 0.0034 | -0.0059 | HOLD |
| 2026-07-15 | baseline_q3_2026 | 480 | 0.8350 | 0.0019 | 0.0000 | CHAMPION |
| 2026-11-13 | cand_direct_q4_2026 | 480 | 0.8621 | 0.0125 | 0.0271 | HOLD |
| 2026-11-13 | cand_stress_q4_2026 | 480 | 0.8563 | 0.0024 | 0.0213 | PROMOTE |
| 2026-11-13 | cand_calib_q4_2026 | 480 | 0.7772 | 0.0018 | -0.0578 | HOLD |
