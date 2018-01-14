# plant_seeding
Classified 12 species of plants as part of Kaggle Competition.
My score in the Leaderboard for the best submission is 0.98488, and it is at 22nd position out of 350(Top 7%) on 14th Jan,2018

| File Name | Description | Kaggle LB score (F1 score) |
|--|--|--|
| 01_image_size_selection.ipynb | Analysed the train image sizes | - |
| 01_train_validation_split.ipynb | Divided the given train data into train and validation sets with a ratio of 4:1 |   -  |
| 02_VGG_from_scratch.ipynb | Trained all the layers of VGG-16 model initialised with random weights, image size-196x196 | 0.93450 |
| 03_VGG16_fixed_bottom.ipynb | Finetuned the bottom layers of VGG-16 model initialised with imagenet weights, image size-224x224 | 0.93073 |
| 04_ResNet_from_scratch.ipynb | Trained all the layers of ResNet50 model initialised with random weights, image size-224x224 | 0.92695 |
| 05_Resnet_fixed_bottom.ipynb | Finetuned the bottom layers of ResNet50 model initialised with imagenet weights, image size-224x224 | 0.93702 |
| 06_Inception_from_scratch.ipynb | Trained all the layers of Inception model initialised with random weights, image size-299x299 | 0.92821 |
| 07_Inception_fixed_bottom.ipynb | Finetuned the bottom layers of Inception model initialised with imagenet weights, image size-224x224 | - |
| 08_1_MobileNet_from_scratch.ipynb | Trained all the layers of MobileNet model initialised with imagenet weights, image size-224x224 | 0.96977 |
| 08_2_MobileNet_from_scratch-second_split.ipynb | Trained all the layers of MobileNet model initialised with 08_1 model's weights and averaged the outputs, image size-224x224 | 0.96851 |
| 09_mobilenet_oversampling.ipynb | Trained MobileNet model initialised with 08_1 model's weights doing oversampling, image size-224x224 | - |
| 10_mobilenet_two_models.ipynb | Created a binary classifier to classify between 'Black-grass' and 'Loose Silky-bent' using MobileNet model initialised with imagenet weights, and appended this model to our previous 08_1 model, image size-224x224 | 0.89672 |
| 11_mobilenet_two_models_V2.ipynb | Using model 10, but initialised with 08_1 model's weights and training only the bottom layers, image size-224x224 | 0.96599 |
| 11_mobilenet_two_models_V3_1st_split.ipynb | Using model 11 with version V2, initialised with 08_1 model's weights, but trained all the layers, image size-224x224 | 0.97229 |
| 11_mobilenet_two_models_V3_2nd_split.ipynb | Using model 11 with version V3, initialised with 08_2 second_split model's weights, and averaged the 11-V3 1st split and 2nd split weights, image size-224x224 | 0.97607 |
| 12_1_MobileNet_1500px_1st_data_split.ipynb | Using model 08_1, initialised with 08_1 model's weights, image size-1500x1500 | 0.97858 |
| 12_1_MobileNet_1500px_fixed_bottom.ipynb | Using model 12_1 1st data split, initialised with it's weights and training only the bottom layers, image size-224x224 | - |
| 12_2_MobileNet_1000px_2nd_data_split.ipynb | Mobilenet model initialised with 08_1 model's weights but trained on second split with image size 1000x1000, and averaged the outputs | 0.98362 |
| 12_3_mobilenet_two_models_V3_size_increase.ipynb | binary classifier with image size 1500x1500, initialised with 12_1 model's weights | 0.97229 |
| 13-MobileNet-1500px-PseudoLabelling.ipynb | With model 02_1, performed pseudo-labelling, image size-1500x1500 | 0.97609 |
| 14_ensemble_of_models.ipynb | Different Kinds of ensembles of previous models | 0.98488 |
