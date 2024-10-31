## SECTION 1 : PROJECT TITLE
## Retinanet

---

## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT

**Key Components**:​ Access to quality medical care remains a critical challenge in many developing countries, particularly in specialized areas like ophthalmology. Inadequate resources and a shortage of trained professionals often result in significant delays in diagnosis and treatment, leading to the progression of preventable or treatable eye conditions. This not only exacerbates the burden of vision-related disabilities but also impacts the overall health and productivity of affected individuals. 

In response to these challenges, our project aims to leverage advanced technology to enhance the accessibility and efficiency of eye care. By developing a sophisticated classification system that utilizes machine learning and deep learning techniques, we seek to provide rapid and accurate diagnoses of common eye diseases such as Diabetic Retinopathy, Cataract, and Glaucoma through the analysis of retinal images. This initiative promises to deliver instant feedback to healthcare professionals and patients, particularly in remote regions where access to specialized care is limited. 

This report outlines the objectives, methodologies, and anticipated impact of our project, highlighting how innovative technological solutions can transform eye care delivery and ultimately improve health outcomes for vulnerable populations. 

**Goals**:​ Retinanet is web-based eye disease detection application which will integrate the best machine learning architecture out of the three approaches done in the project

Based on the Result and Analysis, out of the 3 versions, Version-3 architecture gives the most efficient and interpretable results. So, Version-3 is deployed as the final classifier for Eye disease detection. 

Implementation is done using Grad-CAM and Flask as described below. 

A web-based product for Eye disease prediction.​
---

## SECTION 3 : CREDITS / PROJECT CONTRIBUTION
<img width="491" alt="image" src="https://github.com/user-attachments/assets/5d8b040b-c53a-428b-bc08-c27fbb0ac834">

---

## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

Please find the video here, https://drive.google.com/file/d/1LFUOjjSf0pKWQF8VidZXKeOYd4gCi3mK/view?usp=sharing 

---

## SECTION 5 : USER GUIDE

1. Installation
 
Prerequisites:
   - Python 3.8 or higher
   - Flask
   - Necessary libraries (e.g., CV2, TensorFlow, NumPy, Pandas, sklearn)
   - NOTE: MAKE SURE THAT THE BELOW MENTIONED DATASET IS PRESENT IN THE SAME FOLDER AS THE .ipynb file
   - Download the dataset from this drive link,
     - ODIR-5K - https://drive.google.com/drive/folders/1vg4fkEa8aMBzfdecoZgKLmMlZAdSkoSO?usp=sharing
     - Cataract dataset - https://drive.google.com/drive/folders/1RVwudczOU84nQnypzwSTtzdh2881y42G?usp=sharing
     - Diabetes Retinopathy dataset - https://drive.google.com/drive/folders/1Wfp6T-obd3Af51rzBn4Osx3SOcFA8QtH?usp=sharing
     - Glaucoma dataset - https://drive.google.com/drive/folders/1GuijSyWLBMIWDr52vz5Q5M5hHVrWmz8-?usp=sharing
   - Find the weights of the model in the below drive link
     - https://drive.google.com/drive/folders/1rnf9pC9X0oCdQ1inOyDVkLABiJeJHMmx?usp=sharing

Steps:
   1. Clone the repository
   2. Navigate to the System code and download the flask_implementation file
   3. Unzip the file.
   4. Install dependencies:
pip install -r requirements.txt
   5. Start the Flask server:
  	       	python app.py
   6. Open the application in a browser at `http://127.0.0.1:5000`.
 
2. User Guide
 
Navigating the Application:

 
Features:

 
Error Handling:


---
## SECTION 6 : PROJECT REPORT / PAPER

`Refer to project report at Github Folder: ProjectReport`

** Sections for Project Report / Paper:**
- Executive Summary / Paper Abstract
- Business Problem Background
- Market Research
- Project Objectives & Success Measurements
- Project Solution 
- Project Implementation 
- Project Performance & Validation 
- Project Conclusions: Findings & Recommendation
- Appendix of report: Project Proposal
- Appendix of report: Mapped System Functionalities against knowledge, techniques and skills of modular courses
- Appendix of report: Installation and Use

## SECTION 7 : MISCELLANEOUS

`Refer to Github Folder: Miscellaneous`
