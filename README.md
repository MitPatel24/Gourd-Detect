# Gourd Detect: Visually Similar Vegetable Detection and Identification in Market Environments 🥒

  
**Motivation:**  
The goal of this project is to create a system capable of detecting and identifying visually similar vegetables in a market environment 🛒. The focus is on five common vegetables that often look alike: Sponge gourd, Cucumber, Ridge gourd, Bottle gourd, and Bitter gourd. The system will detect these vegetables using deep learning and computer vision techniques. 🥒👀

---

## Dataset Creation 📸  
The dataset for this project was gathered by taking pictures in a market environment. It includes images captured by the user and supplemented by images from an existing dataset and Google. All images were annotated to be used with YOLO (You Only Look Once) for training the object detection model.

<img width="210" alt="Dataset" src="https://github.com/user-attachments/assets/d8d59b48-a379-48f8-bab7-5b4727221298">

## 📂 **Features**  
- Detects visually similar vegetables like Sponge gourd, Bottle gourd, Ridge gourd, Bitter gourd, and Cucumber.  
- Custom dataset creation with YOLO-compatible annotations.  
- YOLOv8-based model training for high-accuracy detection.  
- Intuitive inference with bounding box visualization.  
---

  
### ⚙️**Prerequisites**   
* Ensure the following libraries are installed with the specified versions: 

    ```bash
        opencv-python==4.10.0.84  
        numpy==1.26.4  
        matplotlib==3.9.3  
        pandas==2.2.2  
        ultralytics==8.3.48  
        shutil 

## **Future Scope** 🚀 
The project can be extended by improving dataset diversity, optimizing the model for real-time inference, and integrating the system with an automated checkout system for smart supermarkets. The detection can be enhanced to cover more vegetable types with minimal false positives.


## **Contributors**
- Mitkumar Patel -  [MitPatel24](https://github.com/MitPatel24)
