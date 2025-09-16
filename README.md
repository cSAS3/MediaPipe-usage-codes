# LaptopCam_1Person_Holistic_Analyzer

Single-person video analysis (Pose + Hands + Lips) with mirror-safe overlay and CSV outputs on Google Colab.

## Open in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/<YOUR_GITHUB_USER>/<YOUR_REPO>/blob/main/notebooks/LaptopCam_1Person_Holistic_Analyzer.ipynb)

## What you get
- overlay_detailed.mp4 / overlay_simple.mp4
- *_landmarks_long.csv (tidy)
- *_summary_metrics.csv
- *_schema_and_legend.json (colors, labels, orientation notes)

## Notes
- Analysis runs on **mirrored frames**, outputs are saved in the **original orientation**.
- Do not commit personal videos; add outputs to `.gitignore`.

## License
MIT
