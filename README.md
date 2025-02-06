# **Face Detection Using Machine Learning**

### **Project Overview**
This project involves training a **face detection model** using machine learning techniques to recognize and classify faces of the two project members: **Abdullah Mehtab** and **Faizan Imtiaz Cheema**. The model was trained using a dataset of **205 images** and tested on a separate set of images.

The primary goal of this project was to **develop a machine learning model capable of distinguishing between the two faces** using image classification.

---

## **Project Structure**
```
|-- Project_COMP102_(Abdullah_Mehtab_&_Faizan_Imtiaz_Cheema).ipynb  # Main Jupyter Notebook
|-- Report document for project (By Abdullah Mehtab).docx           # Project Report
|-- dataset/                                                        # Training Images
    |-- Abdullah/                                                   # Images of Abdullah
    |-- Faizan/                                                     # Images of Faizan
|-- models/                                                         # Trained models
|-- results/                                                        # Output Images
```

---

## **Dataset Details**
- **Total images:** **205**
  - **Abdullah Mehtab:** **100 images**
  - **Faizan Imtiaz Cheema:** **105 images**
- **Training & Testing Split:** 
  - **80% training** (164 images)
  - **20% testing** (41 images)
- **Annotation Files:** XML files for each image (not included in count).

---

## **Model Training Details**
- **Total training steps:** **10,000**
- **Training Time:** **~5 hours**
- **Framework Used:** TensorFlow/Keras with OpenCV (based on analysis of structure)

---

## **Testing and Results**
- **Test images used:** **4 total**
  - **2 images of Faizan Imtiaz Cheema**
  - **2 images of Abdullah Mehtab**
- The model successfully detected and classified the faces correctly in test images.

---

## **Requirements**
To run this project, install the following dependencies:

```bash
pip install tensorflow opencv-python numpy matplotlib
```

---

## **Running the Project**
1. Open **Jupyter Notebook** and run the `Project_COMP102_(Abdullah_Mehtab_&_Faizan_Imtiaz_Cheema).ipynb` file.
2. The notebook will:
   - Load the dataset
   - Train the model on the images
   - Evaluate the model on test images
   - Display the detection results
3. Adjust hyperparameters if needed to improve model accuracy.

---

## **Future Improvements**
- **Expand the dataset** to include more diverse images for better generalization.
- **Optimize model training** to reduce computation time.
- **Enhance face detection accuracy** using more advanced architectures like CNNs.

---

## **Authors**
- **Abdullah Mehtab**
- **Faizan Imtiaz Cheema**

This project was developed as part of **COMP102** coursework.
