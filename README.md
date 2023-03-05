# Document Image Classification
We have a set of grayscale document images and the task is to classify each image into one of the 16 classes or document types. The training dataset which we have used is an RVL-CDIP dataset that consists of 16000 images with ~1000 images belonging to each class. The validation dataset consists of 900 images.

In our approach, we employ pre-trained CNNs & Transformers using the concept of Transfer Learning to perform Image Classification.

## Results
∗ Boosted accuracy score by 15% by appending a Supervised Contrastive loss function to the ResNET module \n
∗ Improved acc by 29% with bootstrap aggregation of MobileViT, MobileNet models achieving 77% overall accuracy
