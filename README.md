# Low Memory Training and Inference with VGG16
<p align="justify">

This code repository is the result of my undergraduate thesis project. The purpose of this project is to train the model using 3 techniques (Low Precision, Microbatching, & Sparsity) and then evaluate the training and inference performance of VGG16 models. The training performance of each model is measured by how much model memory, activation memory, optimizer memory, & training time it requires to train each model. Whereas the inference performance of each model is measured by how much model memory, activation memory it requires to do inference of 1 batch of image, how accurate each model is, and also by how many images does the model can inferred in 1 second.

This code is run in Python 3.8.1 environment and use CUDA 11.2 and cuDNN 8 for training with NVIDIA GPU. As for the library needed to train and make inference with the models is already provided in requirements.txt file. 
</p>

# Additional Links
As for the link to the thesis can be accessed through this google drive link: https://docs.google.com/document/d/1XqSFGuMd0BBAJyQIJC_TEcZDmjS-0Z8T/edit?usp=sharing&ouid=109370577966711764027&rtpof=true&sd=true </br>
Link to dataset the is used in this project -> https://drive.google.com/drive/folders/1HmhhPUqU-Wv8VGsZV8iusO3kKnVkzmaw?usp=drive_link</br>
Link to all trained VGG16 Models -> https://drive.google.com/drive/folders/1-8Y8a1RTt-6ym7iYLeLLwweTgNJzunP3?usp=sharing</br>


