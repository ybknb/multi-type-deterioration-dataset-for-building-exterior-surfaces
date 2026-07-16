# multi-type-deterioration-dataset-for-building-exterior-surfaces

Multi-Type Deterioration Dataset for Building Exterior Surfaces



Overview



This repository hosts a \*\*representative sample set\*\* of the multi-type deterioration dataset for building exterior surfaces. The full dataset is available upon reasonable request.



The deterioration types covered include:

\- Cracks (linear deterioration)

\- Peeling (planar deterioration)

\- Mold spots (planar deterioration)

\- Water seepage (planar deterioration)



&#x20;Sample Dataset



A small representative sample is provided in the `/sample/` directory to demonstrate:

\- Image capture conditions and quality

\- Annotation format

\- QR code scale referencing methodology



&#x20;Full Dataset Access



The complete dataset used in this study is \*\*not fully publicly available\*\* due to:

\- Privacy and ethical restrictions related to building location information;

\- Large volume of raw high-resolution images exceeding repository limits.



To request the full dataset, please contact the corresponding author with:

1\. A brief description of intended research use;

2\. Affiliation information;

3\. Agreement to non-commercial academic use.



Benchmark Results



| Task | Model | Metric | Value |

|------|-------|--------|-------|

| Object Detection | Improved YOLOv11n | mAP@0.5 | 87.93% |

| Object Detection | Improved YOLOv11n | Parameters | 2.58M |

| Object Detection | Improved YOLOv11n | Inference Speed | 37 FPS |

| Segmentation | U-Net | IoU | 94.11% |

| Quantification | — | Area Error (Planar) | 2.84% |

| Quantification | — | Length Error (Crack) | 6.23% |

| Quantification | — | Width Error (Crack) | 5.77% |



Citation



If you use this dataset in your research, please cite:



License



This sample dataset is released under the MIT License.

