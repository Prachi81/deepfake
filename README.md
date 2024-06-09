# Deepfake Video Detection Using ResNet and LSTM Models

What is Deepfake?
Deep fake is a technique for human image synthesis based on artificial intelligence.

Detecting deep fake videos is addressed using three different models: ResNet101, ResNet50, and ResNet152, each integrated with LSTM (Long Short-Term Memory) layers.
![image](https://github.com/Prachi81/deepfake/assets/141800852/4eb98800-add6-4bbd-ac3c-728042b9cb94)

Dataset Description:
The dataset choosen is Celeb-DF-v2. This dataset contains total 1,518 real and fake videos
https://github.com/yuezunli/celeb-deepfakeforensics?tab=readme-ov-file
![image](https://github.com/Prachi81/deepfake/assets/141800852/fb998196-9825-486b-b365-7775d276a7a1)

Preprocessing videos: preprocessing file use to proprocess all the video

TrainModels: contains files to train models ResNet50, ResNet152 and ResNext101 with lstm
model checkpoints: https://drive.google.com/drive/folders/1sHts-0k7py0TVjjYzVhcgmgxQAD5Nvjp?usp=sharing

Results indicate that ResNet101 combined with LSTM achieved the highest accuracy of 91.78%, followed by ResNet152 with LSTM at 90.35%, and ResNet50 with LSTM at 90.23%. These findings demonstrate the effectiveness of using deep neural networks enhanced with LSTM layers for deep fake detection, with ResNet101 showing the best performance.

![image](https://github.com/Prachi81/deepfake/assets/141800852/2d7739db-9568-45d5-8f3d-10395e453a6d)
