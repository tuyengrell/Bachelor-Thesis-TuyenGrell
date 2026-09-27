# Cued AAT

- `preprocess_lmer_cuedtask.py` – gaze-based and accuracy exclusions, RT cleaning,
  intensity coding; writes the trial table and the exclusion funnel (Fig. 3.5)
- `lmer_cuedtask.py` – linear mixed model (Section 4.1, Appendix C.1), intensity
  robustness checks, Fig. 4.3

Expected raw files in this folder: `reactionTime`, `cueSide`, `pictureSequence`,
`reactionPerformed`, `pictureTimeIdx`, `fixationTimeIdx`, `timeVectorContinuos`,
`x/yPositionLeft/RightContinuos` (`.mat`) and `results/block_order.csv`.
