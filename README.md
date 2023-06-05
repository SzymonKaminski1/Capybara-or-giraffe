# Capybara-or-giraffe
This project is about using CNN model to classify capibara and giraffe. During my work on this project I decided to use VGG19 model with data augmentation. I am using ROC curve AUC score to measure performance of my model. I am also using some test cases to figure out some features of prediction and to satisfy my curiosity.\
I am curently working on my own architecture to get the result I want.

Source of images I used for trainig is: https://www.kaggle.com/datasets/jirkadaberger/zoo-animals. In 'giraffe' images there was a group of images which were frames from one movie. I decided to delete them manually, because I think they would disturb learning process. I also decided to delete some random photos from 'capybara' part to make even amount of data for these two classes.

My final goal is to correctly classify photo of giraffe figurine I got from my girlfriend.

<p align="center">
  <img width="270" height="360" src="https://github.com/SzymonKaminski1/Capybara-or-giraffe/assets/116368901/ba3f2023-02d3-4cd8-baaf-c6732e7df42d">
</p>
I also want to confuse my model using this mysterious image!

<p align="center">
  <img width="360" height="360" src="https://github.com/SzymonKaminski1/Capybara-or-giraffe/assets/116368901/55496b57-b7ec-4398-a560-7faca04ee37c">
</p>
