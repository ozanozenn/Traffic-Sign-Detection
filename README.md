# Traffic Sign Detection 🚦

This project focuses on detecting and classifying traffic signs using state-of-the-art computer vision techniques. It provides a complete pipeline for real-time traffic sign detection in images and videos. The project is powered by YOLOv4 for object detection and a custom CNN classifier for traffic sign recognition.


# Features 🌟
Image and Video Detection: Detects traffic signs in static images and video feeds.
YOLOv4 Integration: Efficient and real-time object detection.
Custom CNN Classifier: Classifies detected traffic signs into predefined categories.
Scalable Architecture: Easily extendable for additional sign types or real-world deployment.

# Roadmap 🛠️
Follow these steps to set up and run the project:

### Step 1: Clone the Repository
“`git clone https://github.com/ozanozenn/Traffic-Sign-Detection.git
cd Traffic-Sign-Detection“`
### Step 2: Install Dependencies

“`
Install the required Python libraries:
pip install -r requirements.txt
“`

### Step 3: Download the Dataset and Models
Due to file size limitations, the dataset and pretrained models are not included in this repository. You can download them from the following links:

- Dataset: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
- YOLOv4 Weights: Download from Official YOLO Website
- Trained CNN Model: Download from Google Drive

### Step 4: Run the Project
- For Image Detection
Open the yolov4_image_detector.ipynb notebook and execute the cells step by step.

- For Video Detection
Open the yolov4_video_detector.ipynb notebook and execute the cells step by step.

- For Training the Classifier
To retrain or fine-tune the CNN classifier, open the cnn_classifier.ipynb notebook and follow the steps.


### Outputs 📸
**Below are some sample outputs of the project:**

- Image Detection:
- Video Detection:

![Traffic Sign Detection Output](Traffic_Sign_Classification_Detection/results/videos/res.gif)


