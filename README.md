# Diabetic-Retinopathy
Diabetic retinopathy (DR) is an eye disease triggered due to diabetes, which may lead to blindness.Blood sugar levels that are abnormal in the human body accumulate in blood vessels as glucose is converted into energy. Diabetic retinopathy (DR) develops when a patient has had diabetes for more than ten years. DR occurs due to high blood pressure and causes damage to the retina, and it damages the retinal vascularization, which may cause blindness and death.By 2030, there are estimated to be 552 million diabetic patients worldwide, and DR is a leading cause of blindness. To prevent diabetic patients from becoming blind, early diagnosis and accurate detection of DR are vital.

Dataset Description -
The Gaussian Smoothing Operator performs a weighted average of surrounding pixels based on the Gaussian distribution. It is used to remove Gaussian noise and is a realistic model of defocused lens. The dataset is gaussian filtered and resized to 224x224 pixels image size.

Approach towards problem statement-
CNN - Convolutional Neural Networks (CNNs) are a type of deep learning (DL) model that can be used to detect diabetic retinopathy (DR) in eye images. CNNs can learn patterns from fundus images and classify blood vessel pixels to identify the severity of DR. CNNs can be more effective than manual diagnosis by ophthalmologists, which can be time-consuming, expensive, and prone to error.

Pretrained - Transfer learning is a technique in machine learning where a model trained on one task is used as the starting point for a model on a second task. This can be useful when the second task is similar to the first task, or when there is limited data available for the second task. By using the learned features from the first task as a starting point, the model can learn more quickly and effectively on the second task. This can also help to prevent overfitting, as the model will have already learned general features that are likely to be useful in the second task.

Ensemble - Ensemble models are used to detect diabetic retinopathy (DR) because they can be more accurate and stable than single models. There are two main reasons to use an ensemble-based over a single-based model, Performance, and Robustness; an ensemble can make better predictions and achieve better performance than any single contributing model.

Binary Classification - Binary classification is a technique used to detect diabetic retinopathy (DR) in color fundus images by distinguishing between a healthy retina and a diseased one. In binary classification, all non-DR images are classified as normal and all DR images are classified as abnormal, regardless of the grade of retinopathy.

The users can enter their scan in the link provided and the model will categorise the scan as a DR or No DR scan, with a categorisation of the stage of DR.
