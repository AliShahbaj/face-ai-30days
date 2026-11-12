# Day 1 – Face Recognition Fundamentals

## 5 Key Takeaways

### 1. Face Detection
Face Detection identifies the location of human faces in an image or video. It usually returns bounding boxes around detected faces.

### 2. Face Alignment
Face Alignment adjusts face orientation and position using facial landmarks such as eyes, nose, and mouth.

### 3. Face Embedding
Face Embedding converts a face image into a numerical feature vector using a neural network. Common dimensions include 128D and 512D.

### 4. Face Verification (1:1)
Verification compares two face embeddings to determine whether they belong to the same person.

Example: Smartphone face unlock.

### 5. Face Identification (1:N)
Identification compares one unknown face against multiple registered identities to find a possible match.

Example: Employee identification system.

## Complete Face Recognition Pipeline

Detect → Align → Embed → Match

## Day 1 Learning Summary

I learned the basic Face Recognition pipeline, the difference between detection, verification and identification, and prepared my Python computer vision development environment using OpenCV, NumPy, Matplotlib and Jupyter.

**Next Goal:** Learn image processing with OpenCV.