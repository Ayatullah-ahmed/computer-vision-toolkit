# Computer-Vision-Toolkit

This repository serves as a centralized hub for a collection of PyQt-based desktop apps focused on computer vision techniques, including image processing, segmentation, feature extraction, thresholding, and face recognition.

## Image-Filter

### Overview
A module for applying advanced image filtering techniques to enhance image quality and prepare data for analysis.

### Screenshots

| Feature      | Image                                      | Description                                      |
|--------------|--------------------------------------------|--------------------------------------------------|
| Mixer Mode   | ![Mixer Mode](https://github.com/user-attachments/assets/e069bfc4-9c2c-4921-85dc-3fe384f70a74) | Blend two images using frequency-domain manipulation. |
| Sobel        | ![Sobel](https://github.com/user-attachments/assets/2c2cf097-2c6b-4b2f-a537-1a146226693f) | Detects edges using gradient approximation.     |
| Canny        | ![Canny](https://github.com/user-attachments/assets/6a1bd53a-2be6-4287-a774-660863b46946) | A multi-stage algorithm for optimal edge detection. |


## Object-Segmentation

### Overview
An application implementing sophisticated segmentation algorithms to isolate objects within images for detailed region analysis.

### Screenshots

| Feature              | Image                                      | Description                                      |
|----------------------|--------------------------------------------|--------------------------------------------------|
| Snake-Active-Contour | ![Snake-Active-Contour](https://github.com/user-attachments/assets/e5fab0cb-01ca-4316-8964-045104977918) | Evolves an initial contour using internal, external, and balloon energies. |
| Canny-Edge-Detection | ![Canny-Edge-Detection](https://github.com/user-attachments/assets/3f798a81-7aff-4702-9cd1-a05f42698f1d) | Detects edges with Gaussian smoothing and double thresholding. |
| Hough-Transform-Ellipse | ![Hough-Transform-Ellipse](https://github.com/user-attachments/assets/f70348b3-4f3f-422f-9418-99b83513dd36) | Fits ellipses to contours with area filters.     |


## Image-Descriptor

### Overview
A tool for extracting and describing key features from images, supporting recognition and matching tasks.

### Screenshots

| Feature              | Image                                      | Description                                      |
|----------------------|--------------------------------------------|--------------------------------------------------|
| Harris-Corner-Detection | ![Harris-Corner-Detection](https://github.com/user-attachments/assets/e5508ce6-f9d2-432b-8910-6830e1a73ef2) | Detects corners using Sobel gradients and Harris response. |
| SIFT-Keypoint-Detection | ![SIFT-Keypoint-Detection](https://github.com/user-attachments/assets/58a2e215-3ec5-4e8f-bb3f-738af8db7cb4) | Detects keypoints with Gaussian and DoG pyramids. |
| Draw-Matches         | ![Draw-Matches](https://github.com/user-attachments/assets/f566d2ac-cc30-4494-a5df-456684509ef6) | Visualizes matches with green circles and colored lines. |


## Image-Thresholding-Segmentatio

### Overview
A versatile app combining thresholding and segmentation methods to convert images into binary formats and cluster pixels effectively.

### Screenshots

| Feature              | Image                                      | Description                                      |
|----------------------|--------------------------------------------|--------------------------------------------------|
| Otsu-Global-Thresholding | ![Otsu-Global-Thresholding](https://github.com/user-attachments/assets/d6ae4ec2-1045-4da0-a8c0-4112ab993962) | Minimizes intra-class variance globally.         |
| K-Means-Clustering   | ![K-Means-Clustering](https://github.com/user-attachments/assets/01ace9f1-1775-4886-bc6d-4a82647ed7bb) | Clusters pixels by assigning to k centers.       |
| Region-Growing-Segmentation | ![Region-Growing-Segmentation](https://github.com/user-attachments/assets/b887f50e-10e0-44c1-ba3a-d89172ec5c33) | Grows regions from seed points using BFS.        |


## Face-Recognition-and-Detection

### Overview
A system for detecting faces using Haar Cascades and recognizing individuals with the ORL dataset using PCA and SVM.

### Screenshots

| Feature              | Image                                      | Description                                      |
|----------------------|--------------------------------------------|--------------------------------------------------|
| Face Detection       | ![Face Detection](https://github.com/user-attachments/assets/263ac9ff-b051-4218-9317-f388d2fefff5) | Detects faces with Haar Cascades and draws rectangles. |
| Face Recognition     | ![Face Recognition 1](https://github.com/user-attachments/assets/15025e14-570e-493d-b104-4c8daa7244b8) | Recognizes faces with PCA and SVM on ORL dataset. |
| ROC Curve            | ![ROC Curve](https://github.com/user-attachments/assets/23dec072-d9e5-4645-941a-e5bbf2ccae3b) | Plots TPR vs. FPR for multi-class performance.   |


## Getting Started

1. Clone the repository with submodules:
   ```bash
   git clone --recurse-submodules https://github.com/Ayatullah-ahmed/Computer-Vision-Toolkit.git
   ```
   If submodules are not cloned, initialize and update them:
   ```bash
   git submodule update --init --recursive
   ```
2. Install dependencies (e.g., PyQt, OpenCV, NumPy, Cython) for the main toolkit and each submodule.
3. Navigate to each submodule directory and follow its specific setup instructions.
4. Run the main UI to access all integrated tools.

## Contributors

<table>
  <tr>
        <td align="center">
      <a href="https://github.com/Abdelrahman0Sayed" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/113141265?v=4" width="150px;" alt="Abdelrahman Sayed"/>
        <br />
        <sub><b>Abdelrahman Sayed</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/salahmohamed03" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/93553073?v=4" width="150px;" alt="Salah Mohamed"/>
        <br />
        <sub><b>Salah Mohamed</b></sub>
      </a>
    </td>
        <td align="center">
      <a href="https://github.com/Ayatullah-ahmed" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/125223938?v=4" width="150px;" alt="Aya Ahmed"/>
        <br />
        <sub><b>Aya Ahmed</b></sub>
      </a>
    </td>
        <td align="center">
      <a href="https://github.com/AhmeedRaafatt" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/125607744?v=4" width="150px;" alt="Ahmed Raafat"/>
        <br />
        <sub><b>Ahmed Raafat</b></sub>
      </a>
    </td>
  </tr>
</table>
