# DDD - A Diagnostic Dataset for Character Recognition and Detection on Ancient Egyptian Hieratic Characters and Words

![Section of an ancient Egyptian papyrus with hieratic writing. Some characters and character groups are annotated with colourful polygonal bounding structures. The corresponding class labels have been printed on top in white, labels like "G7" or "Q3" or "Wr".](./imgs/polygons.jpg)

This respository contains code and supplementary material for the paper "DDD - A Diagnostic Dataset for Character Recognition and Detection on Ancient Egyptian Hieratic Characters and Words", presented at the International Conference on Document Analayis and Recognition (ICDAR) 2026 and provides first baselines for the recognition and detection of ancient Egyptian hieratic characters for the [Diagnostic Deir el-Medina Dataset (DDD)](https://doi.org/10.5281/zenodo.20553713).


## Content

The paper presents several baselines for character recognition and character detection on ancient Egyptian hieratic characters. We made use of several existing machine learning architectures:

Recognition:
- ResNet50
- YOLOv8-m
- YOLOv8-l
- ViT_b_16
- ViT_b_32
- Swin_v2_b
- CLIP-RN50
- CLIP-ViT-B-16
- CLIP-ViT-B-32
- DINOv3-ViTs16
- DINOv3-ViTb16

Detection:
- YOLOv8-seg-m
- YOLOv8-seg-l
- YOLOv11-seg-m
- YOLOv11-seg-l
- RT-DETR-l

In the subfolder `code`, we provide code for training, inference and evaluation. The subfolder `results` contains additional evaluation metrics and visualised results expanding the data provided in the paper.

## Citation

If you would like to cite this work, please use:

```bibtex
@inproceedings{unter2026ddd,
    title={{DDD - A Diagnostic Dataset for Character Recognition and Detection on Ancient Egyptian Hieratic Characters and Words}},
    author={Unter, Stephan M. and Hertel, Elena L.},
    booktitle={20th International Conference on Document Analysis and Recognition (ICDAR)},
    pages={xxx--yyy},
    year={2026},
    organization={Springer}
}
```

For the dataset, please cite:

```bibtex
@misc{DDD,
    title={{DDD - Diagnostic Deir el-Medina Dataset}},
    author={Unter, Stephan M. and Breineder, Desiree and Gabler, Kathrin and Hertel, Elena L. and Izak, Jessica and Marty, Evelyne and Müller, Matthias and Pietri, Renaud and Polis, Stéphane and Stanic, Klaudija},
    year={2026},
    doi={10.5281/zenodo.20553713}
}
```