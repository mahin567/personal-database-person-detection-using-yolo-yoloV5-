🧠 Model Performance (My Personal Dataset)
Metric	Score
Precision	92%
Recall	90%
mAP	90%

Interpretation:

The model detects people correctly 92% of the time (few false positives).

It successfully finds 90% of all actual persons in the images (few false negatives).

The mAP (90%) indicates strong overall detection performance and reliability.

📑 Comparison with Existing Research
Model	Precision	Recall	mAP
Your YOLOv5 Model	92%	90%	90%
Existing Paper Result	98%	95%	96%

Analysis:

my model performs slightly lower than the published benchmark results.

This difference may be due to:

A smaller or less diverse training dataset.

Fewer training epochs or limited augmentation.

Different lighting, camera angles, or background conditions.

Despite that, my model still demonstrates strong, real-world reliability.

🧩 Result Summary

Precision (92%) → Very accurate detections.

Recall (90%) → Detects most people correctly.

mAP (90%) → Balanced and robust detection capability.

Overall: my YOLOv5 model is performing well, though fine-tuning the dataset or hyperparameters could push it closer to the research-level 96% mAP.
