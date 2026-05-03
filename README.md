# ResinNet
Deep learning for plastic resin identification using CNNs and Vision Transformers. We use the WaDaBa dataset for a significant portion of model training and testing [see Bobulski & Piatkowski (2018), and Bobulski & Kubanek (2021)]. 


### Links to Packages we are using:

- [resnet50](https://docs.pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html) — Torchvision main documentation
- [ResNeXt](https://docs.pytorch.org/vision/main/models/resnext.html) — Torchvision main documentation
- "[vit_b_16](https://docs.pytorch.org/vision/main/models/generated/torchvision.models.vit_b_16.html)” - PyTorch documentation, model from Dosovitskiy et al. (2020)
- https://github.com/microsoft/Swin-Transformer/blob/main/get_started.md - Swin Transformer
- https://github.com/HobbitLong/SupContrast?tab=readme-ov-file - SupConLoss



### File Descriptions:
- **ProjectVisionTransformer.ipynb** - training, validation, and testing of "vit_b_16" model on original WaDaBa imagery.
-  **ProjectVisionTransformerAlteredData.ipynb** - training "vit_b_16" model on original and masked WaDaBa imagery. Testing on both original WaDaBa imagery and our own collected images.



### Notes:
Project Members: Ben Glass, Dani Schwartz, James Wareham. 
Project completed as part of course EC523 (Deep Learning) at Boston University (Spring 2026). 


### References
#### (Formatting follows citation guidlines from the project report)
J. Bobulski, M. Kubanek. Deep Learning for Plastic Waste Classification System. Applied Computational Intelligence and Soft Computing, 2021.

J. Bobulski, J. Piatkowski. PET waste classification method and Plastic Waste DataBase WaDaBa, Advances in Intelligent Systems and Computing, 681: 57-64, 2018.

A. Dosovitskiy, L. Beyer, A. Kolesnikov, D. Weissenborn, X. Zhai, T. Unterthiner, M. Dehghani, M. Minderer, G. Heigold, S. Gelly, J. Uszkoreit, N. Houlsby. An Image is Worth 16x16 Words: Transformers For Image Recognition At Scale, arxiv.org, 2020. 
