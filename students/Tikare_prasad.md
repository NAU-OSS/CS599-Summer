**#Hand Gesture Recognition Based on Convolutional Neural Network (CNN) and Support Vector Machine (SVM)
###Authors: 
Muhammad Afiq Abdull Razak, Shahrani Shahbuddin, Farah Yasmin Abdul Rahman, Yuslinda Wati Mohamad Yusof, Roslina Mohamad, Saiful Izwan Suliman
###Affiliation: 
Universiti Teknologi MARA, Shah Alam, Selangor, Malaysia
###Conference: 
2023 IEEE 14th Control and System Graduate Research Colloquium (ICSGRC)

**Introduction**
The study explores hand gesture recognition, which is vital for human-computer interaction (HCI). The focus is on comparing the effectiveness of CNN and SVM in recognizing hand gestures using skeletal data as features. The goal is to determine which method offers superior accuracy and processing efficiency.

**Methodology**
The research involved several key steps:

**Data Acquisition:** 
Collected images of nine hand gestures ("Call", "Fist", "Live Long", "Okay", "Peace", "Rock", "Stop", "Thumbs Up", "Thumbs Down") using a digital camera. The dataset included 2700 images for training and validation, with 300 samples per gesture, and real-time images for testing.
**Feature Extraction:** 
Used MediaPipe Library to detect 21 key points on the hand, representing the hand skeleton. The coordinates were stored in a CSV file.
**Classification Algorithms:**
**CNN:** 
  Utilized TensorFlow library for training. The model consisted of a linear stack of layers with 512 input nodes and 9 output nodes, using ReLU and SoftMax activation functions.
**SVM:**
  Implemented using SciKit-learn library with an RBF kernel to separate the hyperplane.
**Results and Discussion**
**Accuracy:**
**CNN:** 
  Achieved an overall accuracy of 97.78%. It perfectly recognized seven gestures and had minor errors with "Stop" (86%) and "Call" (94%).
**SVM:** 
  Achieved an overall accuracy of 96.30%. It perfectly recognized seven gestures and had minor errors with "Live Long" (74.67%) and "Thumbs Up" (92%).
**Processing Time:**
**CNN:** 
  Took 8 minutes and 24 seconds to train and validate the dataset.
**SVM:** 
  Took 5 minutes and 16 seconds, demonstrating faster processing compared to CNN.
**Conclusion**
Both CNN and SVM are effective for hand gesture recognition, with CNN slightly outperforming SVM in accuracy but requiring more processing time. The skeletal-based hand detection method proved suitable for feature extraction. Future work could explore optimizing both techniques for better performance and exploring additional gestures or real-time applications.

Link to IEEE paper
**https://ieeexplore.ieee.org/document/10215427**
