# Dual Picture Task

- `preprocess_lmer_dualpicture.py` – picture-dwell and instruction-error exclusions,
  RT cleaning, intensity coding; writes the trial table and the exclusion funnel (Fig. 3.6)
- `lmer_dualpicture.py` – linear mixed model (Section 4.2, Appendix C.2), intensity
  robustness checks, 90 % accuracy sensitivity check, Fig. 4.6

Expected raw files in this folder: `reactionTime`, `side`, `movementType`,
`leftPictureID`, `rightPictureID`, `eyeData`, `timeVector`, `pictureOnsetTime`,
`fixationCrossTime` (`.mat`) and `results/block_order.csv`.
