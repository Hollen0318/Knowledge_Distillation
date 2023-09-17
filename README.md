# Knowledge Distillation for ResNet Architectures #
## Code for Approaches to Knowledge Distillation ##

Knowledge_Distillation_Code file contains methods that allow for the training of:
* ResNet18 
* ResNet50
* Knowledge Distillation (KD) with ResNet50 Teacher ResNet18 Student
* Reversed Knowledge Distillation (Re-KD) with ResNet18 Teacher ResNet50 Student
* Teacher-Free Self Knowledge Distillation
* Teacher-Free Knowledge Distillation Manually-Designated Regularization
* ResNet18 Adversarially Trained (AT ResNet18)
* Teacher-Free Self Knowledge Distillation Adversarially Trained (AT Tf KD-self)
* Teacher-Free Manually-Designated Regularization Adversarially Trained (AT Tf KD-reg)

Adversarial Training uses PGD, found in attacks.py

Vanilla_Distillation file shows the code we used to generate our Vanilla Distillation Results

See [Paper](https://github.com/Hollen0318/Knowledge_Distillation/blob/81f5b9830872194e79c0b366cf5d038e3605fabb/Knowledge_Distillation.pdf) and [Poster](https://github.com/Hollen0318/Knowledge_Distillation/blob/81f5b9830872194e79c0b366cf5d038e3605fabb/Poster_Knowledge_Distillation.pdf)

## References: ##
Distilling the Knowledge in a Neural Network. (2015). Student and Teacher from `Distilling the Knowledge in a Neural Network.´ https://github.com/shriramsb/Distilling-the-Knowledge-in-a-Neural-Network

Pytorch Vision.(2015). ResNet-18 and ResNet-50 from `Deep Residual Learning for Image Recognition.´ https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py
