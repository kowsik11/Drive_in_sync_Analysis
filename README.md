# 🚗 Car Detection, Speed Estimation, and Parking Space Identification

## 🎯 Objectives
1. **Car Counter**: Detect and count the number of moving cars.
2. **Speed of Car**: Estimate the speed of each detected car.
3. **Parking Space**: Identify empty parking spaces and detect when cars leave.

## 📌 Problem Statements
The algorithm should be able to accurately:
1. Detect and count moving cars in various lighting and weather conditions.
2. Estimate the car's speed using visual information, such as calculating the distance traveled over time.
3. Detect empty parking spaces and identify when a car is leaving a parking space.

## ⚙️ Methodology
1. **Original Image**: Capture the original image or video feed.
2. **Object Extraction**: Extract the objects (cars) from the image.
3. **Grayscale & Blur Image**: Convert the image to grayscale and apply a blur to reduce noise.
4. **Binary Image**: Convert the image to binary for easier detection of objects.
5. **Noise Removal**: Remove Salt & Pepper (S&P) noise from the image.

## 🛠️ Tools and Libraries
- **Python**: Core programming language used for implementation.
- **OpenCV**: Library used for image and video processing.
- **Numpy**: For handling array operations and mathematical functions.
- **YOLO**: Object detection algorithm used for detecting cars.

---

Feel free to explore the code, suggest improvements, or contribute to the project!

