# partial-ce-loss-segmentation
Point-supervised remote sensing segmentation using Partial Cross-Entropy Loss
# Partial Cross-Entropy Loss for Remote Sensing Segmentation

Point-supervised semantic segmentation using sparse annotations.

## What this does
- Implements Partial CE Loss that trains on sparse point labels only
- Works on remote sensing land-cover classification (Vegetation, Built-up, Background)
- Experiments on annotation density and loss function comparison

## Results
- Naive CE vs Partial CE: +18 mIoU improvement
- 5pts → 40pts per class: +21 mIoU improvement

## Files
- `partial_CE_segmentation.ipynb` — Full implementation + experiments
- `Technical_Report.docx` — Method + experimental findings
