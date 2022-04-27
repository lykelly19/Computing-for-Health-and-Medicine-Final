# Computing-for-Health-and-Medicine-Final

**Final Project Group 9: Diabetic Retinopathy Detection: Identifying the Severity of Diabetic Retinopathy in Eye Images**  
Brent Garey, Kelly Ly, Ann Men, Bishoy Sargius, and William Zouzas  
COMP.4600/5300 Computing for Health and Medicine  
4/26/2022 

## GitHub Repository:
https://github.com/lykelly19/Computing-for-Health-and-Medicine-Final 

## Overview:
Our goal was to create a model to efficiently and accurately detect the severity of DR in eye images to avoid manual classification by clinicians. We were able to pre-process, augment and split eye images into 4 quadrants. We created Quadrant Based Ensemble Inception V3 (instead of V2) models for each quadrant. We trained and tested the model to detect the severity of DR in eye images.

## Sources:
Source used for dataset: 
[1] "Diabetic Retinopathy Detection." https://www.kaggle.com/competitions/diabetic-retinopathy-detection/ (accessed April 4, 2022).

Source used for implementation method using Quadrant Based Ensemble Inception: 
[2] C. Bhardwaj, S. Jain, and M. Sood, "Deep Learning-Based Diabetic Retinopathy Severity Grading System Employing Quadrant Ensemble Model," (in eng), J Digit Imaging, vol. 34, no. 2, pp. 440-457, Apr 2021, doi: 10.1007/s10278-021-00418-5.

## Libraries used:
- Matplotlib  
- Pandas  
- Pillow  
- NumPy  
- OS  
- Shutil  
- Random  
- Imutils  
- Seaborn  
- Statistics  
- Keras  
- Tensorflow  
- PyTorch  
- Torchvision  

## Required pip installs to run our code:
- opencv-python
- imutils

## File directory:
<pre>
data/
    |_labeled_data/
        |_0/
        |_1/
        |_2/
        |_3/
        |_4/
    |_quadrants/
        |_quadrant_1/
            |_0/
            |_1/
            |_2/
            |_3/
            |_4/
        |_quadrant_2/
            |_0/
            |_1/
            |_2/
            |_3/
            |_4/
        |_quadrant_3/
            |_0/
            |_1/
            |_2/
            |_3/
            |_4/
        |_quadrant_4/
            |_0/
            |_1/
            |_2/
            |_3/
            |_4/
</pre>

## How to compile and execute our code: 
Open the “DR Detection Group 9.ipynb” file using Jupyter Notebook. Click on Cell > Run All.



