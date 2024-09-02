## FoodLabel Dataset

This repository contains the experimental data used for the following paper, which has been accepted for publication at [ICDAR 2024](https://icdar2024.net):

Anna Scius-Bertrand, Atefeh Fakhari, Lars Vögtlin, Daniel Ribeiro Cabral, and Andreas Fischer, **"Are Layout Analysis and OCR Still Useful for Document Information Extraction using Foundation Models?"**. *Proc. 18th Int. Conf. on Document Analysis and Recognition (ICDAR), 2024.*

The original images can be downloaded here:

* FoodLabel (2.12 GB): [FoodLabel-images.tgz](https://www.dropbox.com/scl/fi/sm16j872r51rg1gfyafyg/FoodLabel-images.tgz?rlkey=g1pjtx85xs1bsdm1vug23kgla&dl=0)
* CORDv2Total (1.63 GB): [CORDv2Total-images.tgz](https://www.dropbox.com/scl/fi/h92hyc2yp7m2rgqfmc8zl/CORDv2Total-images.tgz?rlkey=dsp2c1q5ag1unm7v5sof0f9x1&dl=0)

The repository contains:

* Ground truth: The target JSON strings for the LLMs, as well as the bounding boxes of the large crops and the small crops (x, y, width, height).
* OCR: The Textract OCR results for the full size images, the large crops, and the small crops.
* Splits: The IDs used for training, validation, and testing.
* Prompts: The system prompts used for OCR-based and image-based document information extraction.

Please contact the authors if you have any questions.