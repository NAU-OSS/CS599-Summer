# Title: Driver Drowsiness Detection- Innovating Safety with Neural Networks and Fuzzy Logic

**IEEE paper: New method of driver drowsiness detection system based on Fuzzy Logic and Artificial Neural Networks**

[Reference to the paper] (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10548730)

**Authors:** 

+ _Mouhcine Lakhloufi, University of Sidi Mohamed Ben Abdellah, National School of Applied Sciences, Fez, Morocco

+ El Mehdi Mellouli, University of Sidi Mohamed Ben Abdellah, National School of Applied Sciences, Fez, Morocco_

**Abstract**

The study in the paper introduces an advanced method for real-time driver drowsiness detection, leveraging Artificial Neural Networks (ANNs) and Fuzzy Logic (FL). By integrating these technologies, the system aims to improve road safety by early detection of fatigue indicators, crucial in preventing accidents.

**Introduction**

Driver drowsiness poses a significant threat to road safety globally, contributing to numerous fatal accidents. This paper addresses the critical need for reliable detection systems by proposing a novel approach that combines neural networks and fuzzy logic. This synergy aims to emulate human cognitive processes while enhancing adaptability to varying environmental conditions.

**Methodology**

- The paper Utilizes a Multilayer Perceptron (MLP) to analyze facial features, particularly focusing on eye and mouth movements. Trained on a dataset of facial images to recognize patterns indicative of drowsiness.
- Fuzzy Logic (FL) manages the imprecise data by categorizing drowsiness levels into fuzzy sets (e.g., "very awake," "very drowsy"). Includes fuzzification, inference, and defuzzification stages.
- Learns from facial data extracted from images, including metrics like Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR).
- Provides reliable detections when ANN predictions are uncertain, ensuring consistent performance.

**Experimental Setup and Results**

+ A specialized dataset comprising 200 images captured via in-vehicle cameras.
+ Feature Extraction, utilizes facial landmarks to compute EAR and MAR, critical for detecting eye closure and yawning.
+ Dataset split into training (70%), validation (15%), and testing (15%) sets to evaluate system performance.
+ Achieved a detection accuracy of 93.98%, demonstrating effectiveness even under challenging conditions such as noise and varying brightness.

**Conclusion**

The integration of Artificial Neural Network and FL represents a significant advancement in drowsiness detection systems, offering enhanced reliability and adaptability. Future research of the paper will focus on overcoming current limitations to further improve performance, particularly in scenarios involving sunglasses or lighting conditions.
