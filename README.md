# MeXE402 - Mechatronics Engineering Elective 2: Data Science and Machine Learning
## Pair-Based Final Project - OpenCV Basics
## Introduction
Detecting faces in group photos is a vital challenge in computer vision. Unlike single-face detection, it involves handling variations in size, pose, lighting, and occlusion. These complexities arise from diverse expressions, crowded backgrounds, and overlapping faces. Accurate detection is essential for applications like photo tagging, social media analysis, and security surveillance. Advancing this task enhances the effectiveness and versatility of facial recognition systems.

## Dataset Description
<div align="center">
  <img src="https://github.com/user-attachments/assets/9c3e621c-bddb-4bd9-9317-fc6c10bf90d4" alt="Logo_of_TWICE svg">
</div>


What is TWICE? 
TWICE is a highly popular South Korean K-pop girl group formed by JYP Entertainment. Known for their catchy music, energetic performances, and vibrant personalities, TWICE is one of the most successful and influential groups in the K-pop industry. The group is composed of nine members: 
- Nayeon (lead vocalist, lead dancer, and center)
- Jeongyeon (lead vocalist)
- Momo (main dancer, rapper, and vocalist)
- Sana (lead dancer and vocalist)
- Jihyo (leader and main vocalist)
- Mina (main dancer and vocalist)
- Dahyun (main rapper and vocalist)
- Chaeyoung (main rapper and vocalist)
- Tzuyu (lead dancer, vocalist, and visual)
## Abstract
The objective of this project is to develop a system capable of detecting faces in a group photo. Leveraging insights and techniques from a face detection tutorial, we aim to apply these learnings to a chosen image featuring the members of the K-pop group TWICE. The approach involves utilizing advanced computer vision methods to identify and highlight individual faces within the photo. The expected outcome is a processed image where each member of TWICE has their face outlined with a ellipse or rectangular highlight, demonstrating precise and effective face detection. This project underscores the application of computer vision techniques in real-world scenarios.

## Project Methods
Files:
- Import the face cascade classifier file provided in the tutorial video.
- Import the group photo of TWICE members.

Coding:
- Import necessary libraries and functions for face detection.
- Convert the image to grayscale to meet the requirements of the face detection code.
- Apply the face detection algorithm to identify faces in the image.
- Overlay ellipse or rectangular highlights on the detected faces.
- Display the final output image with highlighted faces.

## Conclusion
The project successfully demonstrated face detection in a group photo using a cascade classifier, with accurate identification and highlighting of individual faces. Key findings reveal that the system allows flexibility in customizing the color, shape, and thickness of highlights, and it supports different images, although noisy images with multiple faces may result in some undetected or misidentified faces. Challenges encountered included ensuring the image was converted to grayscale, as the detection algorithm requires this format, and using the correct file path to load the image. Despite these challenges, the code performed accurately on clean images, though noisy images highlighted the need for further optimization to improve robustness. This project underscores the potential and limitations of face detection algorithms in complex scenarios.

## Additional Material
Program demonstration link: https://drive.google.com/file/d/1Ptgz_lJdoHS3NrcmtCZQXZ242y7s0rQe/view?usp=sharing

You can access our code at this link: https://colab.research.google.com/drive/1m8B9muOwGpR_BKvsSncWSfCJckcweDPc?usp=sharing

Before running the code to dataset twice01:
![image](https://github.com/user-attachments/assets/fe35c32e-53f0-4565-b3b2-fba5e7b5c787)


After running the code to dataset twice 01:
![image](https://github.com/user-attachments/assets/b7afa09c-08a1-4de4-997d-86d26ce396cb)
