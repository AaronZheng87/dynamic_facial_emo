# dynamic_facial_emo

This project leverages the **EmoNet** model for dynamic facial emotion recognition tasks. The model used in this project is based on [EmoNet](https://github.com/face-analysis/emonet), an emotion recognition network designed for analyzing facial expressions in images and videos.

## Project Overview

The goal of this project is to apply **EmoNet** to facial emotion recognition in videos, extracting emotion-related features at different layers of the neural network. Specifically, we focus on visualizing the first convolutional layer's feature maps to better understand the network's performance and behavior.

### Current Progress

- The code for static image emotion recognition using EmoNet is available in the following Jupyter Notebook:
  [static_img.ipynb](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/emonet/static_img.ipynb)
  
- The project works on extracting features from video inputs and visualizing the activation maps of the first convolutional layer of the EmoNet model.

### Results

Below are the results from our current experiment:

1. **Original Demo Video**:  
   - The original video used for emotion recognition can be found [here](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/emonet/data/demo_video/demo.mp4).

     ![Original Demo Video gif](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/demo.gif)
   
2. **Feature Map Output (First Convolutional Layer)**:  
   
   - The extracted feature maps of the first convolutional layer from the EmoNet model are visualized in this video:  
     [feature_map_output.mp4](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/emonet/data/output_demo/feature_map_output.mp4).
   
     ![conv1 Demo Video gif](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/feature_map_output.gif)
   
3. **EmoNet First Convolutional Layer Feature Map**:  
   - The first convolutional layer's output, specific to the EmoNet network, can be seen in this video:  
     [feature_map_output_emoconv1.mp4](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/emonet/data/output_demo/feature_map_output_emoconv1.mp4).
   
     ![emoconv1 Demo Video gif](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/feature_map_output_emoconv1.gif)

## Installation and Setup

1. To run the static image emotion recognition, open and run the following notebook:
    [static_img.ipynb](https://github.com/AaronZheng87/dynamic_facial_emo/blob/main/emonet/static_img.ipynb).
    

## References

- EmoNet: [https://github.com/face-analysis/emonet](https://github.com/face-analysis/emonet)

