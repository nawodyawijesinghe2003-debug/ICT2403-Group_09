# Road Surface Degradation Detection using Adaptive Enhancement and Segmentation

## Project Overview

This project focuses on detecting and segmenting road surface degradations from road video footage using classical image processing techniques.

The system processes road videos frame-by-frame, applies adaptive image enhancement, and performs segmentation to identify different types of road degradations.

The project was developed for the ICT2403 Image Processing assignment.

---

# Main Objectives

- Improve road frame quality using adaptive enhancement
- Detect road degradations automatically
- Segment damaged regions from road frames
- Generate final marked outputs and masks
- Evaluate segmentation quality
- Integrate enhancement and segmentation into a single pipeline

---

# Detected Road Degradations

The system detects:

| Damage Type | Visualization |
|---|---|
| Pothole / Surface Damage | Red |
| Alligator Cracking | Green |
| Center Line Degradation | Yellow |

---

# Technologies Used

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

---

# Project Structure

```text
IP_Project/
│
├── Enhacement/
│   ├── Extracted_frames/
│   ├── Enhanced_frames/
│
├── Segmentation/
│   ├── ROI_masks/
│   ├── Lane_masks/
│   ├── Dark_damage_masks/
│   ├── Pothole_masks/
│   ├── Alligator_masks/
│   ├── Combined_masks/
│   ├── Final_segmented_frames/
│   ├── Comparison_results/
│   └── Report_figures/
│
├── Videos/
├── reports/
└── README.md
