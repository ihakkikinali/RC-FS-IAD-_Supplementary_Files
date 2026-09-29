Supplementary result files for JARNAS-1957308.

Main VisA protocol:
- 12 categories, seeds 0-4.
- k=4 unless otherwise indicated.
- Total labelled calibration pool: 30% of the remaining normal pool plus 30 defective images per category.
- Stratified nested split: 1/3 of calibration examples for score-fusion fitting and 2/3 for threshold calibration.
- Threshold calibration data are disjoint from score-fusion fitting data.
- alpha=0.05, beta=0.10.
- THR in the manuscript denotes the fraction of category-seed trials with empirical held-out MDR <= alpha.
- DINOv2-PatchMemory and WinCLIP use the same support/calibration/test splits and the same nested threshold-calibration subset for operational metrics.
- Controlled distribution shifts are applied only to held-out test images while calibration and thresholds remain clean.
- Human-error analysis is a scenario sensitivity analysis, not a human-reader experiment.
- Cost values are normalized scenario units, not monetary estimates; prevalence scenarios reweight class-conditional manual-review rates before applying manual-review cost.

The MVTec block is retained as a secondary benchmark continuity experiment; its k-shot ranking and operational values are held-out empirical results under the calibration-assisted MVTec benchmark protocol.
