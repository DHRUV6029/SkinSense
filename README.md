# SkinSense
__A Web Based Tool that aides medical professionals/patients in early stage detection of Skin related abnormalities__
__INTRODUCTION__ 
The recent emergence of machine learning and deep learning methods for medical image analysis has enabled the development of intelligent medical imaging-based diagnosis systems that can assist physicians in making better decisions about a patient’s health. In particular, skin imaging is a field where these new methods can be applied with a high rate of success.

__Brief Overview Our solution aims to classify 7 common types of skin infections namely__

1. ACTINIC KERATOSES
2. BASAL CELL CARCINOMA
3. BENINGN KERATOSES
4. DERMATOFIBROMA
5. MELANOCYTIC NEVI
6. MELANOMA
7. VASCULAR LESIONS

1. Solution will classify all the 7 classes with considerable precision and accuracy.
2. Solution can be used my medical professional to identify the skin disease it helps automate the identification process.
3. Soultion aims to detect Melanoma which is predominant skin cancer in early stages so lives of the paitents can be saved.


# How to Run
The project contains a folder names web-app
1. Clone the repo to your local directory.
2. Change the AWS S3 bucket URL to your AWS S3 URL.
3. Create a bucket in AWS and upload model.json file with public access enabled.
4. Create another bucket with AWS S3 static web hosting feature enabled and upload the files in webapp folder to the bucket.
5. The URL of the index.html will be the URL of your application.


