# Computer-Vision
Implementation of three image classification models using different combinations of feature descriptors and classifiers to perform Face Covering Detection (FCD).

1. Model 1: Scale-Invariant Feature Transform (SIFT) + Support Vector Machine (SVM)

2. Model 2: Histogram of Oriented Gradients (HOG) + SVM

3. Model 3: Convolutional Neural Network (CNN)

Subsequently, a MaskDetection function was implemented on a personal video, using the best of the three models (CNN).

# Screenshots of video output

1. **Correct Mask**


<img width="500" height="300" alt="download" src="https://github.com/user-attachments/assets/6ef5b349-7ccc-4a37-b809-8b4812d7ea35" />


<img width="500" height="300" alt="download-1" src="https://github.com/user-attachments/assets/d3cc5a1c-d269-4e97-b14a-56a0b85d4e33" />


2. **Incorrect Mask**


<img width="500" height="300" alt="download-2" src="https://github.com/user-attachments/assets/f886dd84-2f55-437c-90a5-dbb5ddb215af" />


3. **No Mask**


<img width="500" height="300" alt="download-3" src="https://github.com/user-attachments/assets/e8849db7-b496-45db-9516-413a20fcd344" />
