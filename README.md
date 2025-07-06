# Final-Degree-Project
Glaucoma is an eye disease that causes progressive and irreparable damage to the optic nerve and is the leading cause of irreversible blindness in the world. One of the main challenges of diagnosis of glaucoma is that it does not present obvious symptoms in its early stages, which results in many patients not being diagnosed until vision loss is considerable.

In this context, the use of convolutional neural networks (CNNs) for the analysis of retinographies, has shown great potential for the early diagnosis of this disease. However, although these models achieve high accuracy rates when evaluated on training-like data, their performance declines significantly when they are confronted with images from different domains, such as other medical centers, instrumentation or populations. This phenomenon is known as the domain generalization problem, and is one of the major obstacles to the implementation of these systems in the medical field.

The aim of this thesis is to address this problem through the design and
subsequent evaluation of a technique that seeks to improve the generalization capacity of the models. Specifically, the idea is based on the creation of segmented images that show only the most relevant areas for glaucoma diagnosis. These simplified images will be used to train the models, with the hypothesis that by eliminating irrelevant information from the image and using only that which is of interest for diagnostic analysis, it is possible to obtain a model capable of improving or maintaining the results in the face of changes in the domain.

For all this, three pre-trained convolutional neural network architectures have been used, such as VGG19, ResNet50 and InceptionV3, which have been trained with the same sets of original retinographies and simplified retinographies. Experiments have been performed comparing the performance of these networks with each other, and evaluating their generalization ability when classify different sets of retinographies from those used in their training.


Link to betters models: https://drive.google.com/drive/folders/1djpfo6z39vQOCnbPQ0bPC9Q8pAsUayIZ?usp=sharing
