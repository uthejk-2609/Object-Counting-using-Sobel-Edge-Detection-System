# Object-Counting-using-Sobel-Edge-Detection-System

Automated counting of stars is an important task in star gaze monitoring application, a major step to be performed in real time scenarios. Our proposed approach provides potential applications in astronomy and astrophysics to detect any anomalies. In the space innumerable stars are present which is difficult to achieve the count and due to its physical properties like intensity variations for visibility. The proposed model overcomes these challenges using Edge Detection algorithms at varied threshold and feature extractions using morphological operations. Discontinuity of star intensity is the fundamental property for edge detection that perform optimised results. The proposed system is based on algorithms like Canny, Sobel, Prewitt, are compared using lower threshold values for optimised results.

![image](https://github.com/user-attachments/assets/ecaf84a0-5c30-44a3-914d-42e4ec32f35f)
Fig. 1: – Pipeline of the proposed methodology

![image](https://github.com/user-attachments/assets/05a37310-3fb9-4c64-8372-9be2f8d2b30c)
Fig. 2: RGB to Gray Scale Image Conversion

![image](https://github.com/user-attachments/assets/9458eb5a-169a-4123-9d96-9a8edcb38253)
Fig. 3: Edge Detection

![image](https://github.com/user-attachments/assets/ebb06cf0-b402-4236-89c5-a2be18857956)
Fig. 4(a): Sobel at lower threshold
Fig. 4(b): Dilated image

![image](https://github.com/user-attachments/assets/f29d8923-3f1c-4a52-b94c-c2972d4702c7)
Fig. 5(a): Filling Holes
Fig. 5(b): Object Removal at Borders

![image](https://github.com/user-attachments/assets/6b46d083-3445-4d6e-bea1-e8a1642d97c6)
Fig. 6(a):  Segmentation
Fig. 6(b): Mask overlay

![image](https://github.com/user-attachments/assets/b8f77250-fba3-4c8a-8d35-30f474129be4)
Fig. 7: – Feature extraction and celestial body counting.

![image](https://github.com/user-attachments/assets/fb668b3e-6b5a-4a45-9127-e0b4e5c04b9a)
Fig. 8: – Experimental work on another celestial image. (a) Original Image - 2196, (b) Bounding Box Counting - 2138
