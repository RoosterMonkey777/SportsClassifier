---
title: SportsClassifier
emoji: 📚
colorFrom: gray
colorTo: yellow
sdk: gradio
sdk_version: 3.39.0
app_file: app.py
pinned: false
license: apache-2.0
---
To test the app: https://huggingface.co/spaces/RoosterMonkey/SportsClassifier

Deep Learning model for computer vision and image classification using CNN architecture. Input image and the model will predict what sport the image is about. Currently the categories are 3 (basketball, soccer, baseball), as it was a protype with great success.  

This application is an end-to-end deep learning app, using best and state-of-art industry practices. From gathering data, cleaning data, applying transforms and data augmentation techniques, training the data, testing on validiation and testing sets, optimizing, deploying model on remote server, and conencting the model and create a front-end for the app.

Seeing ~94% accuracy on validation and testing sets using only ~350 lower end quality images (as they were randomly downloaded through duckduckgo image api, so some images might not have even been to relevant).

![2023-07-28 23_51_24-Gradio](https://github.com/RoosterMonkey777/SportsClassifier/assets/94876933/a50da18c-7406-48fc-a2d1-affb61ae3f8e)
![2023-07-28 23_53_04-Gradio](https://github.com/RoosterMonkey777/SportsClassifier/assets/94876933/cf97f285-2b35-421c-bf52-cef0bd1ebfb5)
![Screenshot 2023-07-28 235206](https://github.com/RoosterMonkey777/SportsClassifier/assets/94876933/c1048dfd-abd0-4918-b243-8cf7150790be)
