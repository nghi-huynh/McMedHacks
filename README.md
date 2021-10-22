# McMedHacks

Lower-grade gliomas (LGG) are a group of WHO grade II and grade III tumors. These groups are infiltrative and tend to recur after surgical resection and expand to a higher- grade lesion. The challenge here is to accurately predict patient outcomes based on histopathological data for these tumors.
To tackle this challenge, I implemented a deep learning model to facilitate the automatic tumor segmentation of this dataset. Specifically, I combined a UNet architecture with residual blocks from a pre-trained ResNet50. Then, I augmented the training dataset and trained this ResUNet model on it.
My ResUNet model achieved a mean IoU score of 90% after training for 50 epochs. Even though this is not a fine-tuned model, its performance is quite surprising. Thus, choosing an appropriate model is a crucial step in any machine learning/ deep learning pipelines. Finally, I will embed this ResUNet architecture into a multimodality model to further expand this project to predict the tumor grade and a patient's overall survival rate. Then, I will deploy this model to provide a more interactive environment.
