# Task 4 – Per-Class AP and mAP (with bar charts)

## Summary
- mAP@0.5:0.95 (COCOeval): **0.04721**
- mAP@0.5 (COCOeval): **0.06929**
- mAP@0.5:0.95 (mean of per-class AP table): **0.34337**
- mAP@0.5 (mean of per-class AP table): **0.50389**
- Precision (Ultralytics): **0.70988**
- Recall (Ultralytics): **0.54220**

## Per-class AP

| YOLO idx | Class | COCO cat id | AP@0.5:0.95 | AP@0.5 |
|---:|---|---:|---:|---:|
| 0 | person | 1 | 0.41612 | 0.61093 |
| 1 | bicycle | 2 | 0.20792 | 0.35212 |
| 2 | car | 3 | 0.29923 | 0.46708 |
| 3 | motorcycle | 4 | 0.30714 | 0.50916 |
| 4 | airplane | 5 | 0.49453 | 0.66641 |
| 5 | bus | 6 | 0.48529 | 0.59624 |
| 6 | train | 7 | 0.49620 | 0.67423 |
| 7 | truck | 8 | 0.26653 | 0.39475 |
| 8 | boat | 9 | 0.16144 | 0.31705 |
| 9 | traffic light | 10 | 0.18431 | 0.36579 |
| 10 | fire hydrant | 11 | 0.45839 | 0.58906 |

## Figure
- Bar chart: `/content/runs/yolo_coco_subset_n11/task4_per_class_ap_barchart.png`

## Files
- Per-class CSV: `/content/runs/yolo_coco_subset_n11/task4_per_class_ap.csv`
- Summary CSV: `/content/runs/yolo_coco_subset_n11/task4_map_summary.csv`
- Predictions JSON: `/content/runs/detect/val8/predictions.json`