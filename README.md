#Face Recognition for Attendee Management
##Overview
This project focuses on face recognition for attendee management, utilizing deep learning techniques to identify and count young actors' faces in a group photo. The project is based on a dataset obtained from [Large Age-Gap Face Verification Dataset](http://www.ivl.disco.unimib.it/activities/large-age-gap-face-verification/)
, which contains young and adult faces of celebrities. The adult faces are removed to create a sub-dataset consisting only of young faces, which are then augmented to expand the dataset. The goal is to develop a system capable of predicting the identities of young actors in a group photo and counting the number of attendees.

##Methodology
The project involves the following steps:

Data Preprocessing: Removal of adult faces and augmentation of young faces to create a diverse dataset.
Face Detection: Utilization of Haar Cascade and FaceNet for face detection in images.
Model Training: Implementation of LBPH, ArcFace, and FaceNet for training the face recognition model.
Group Photo Analysis: Application of the trained model to predict the identities of actors in a group photo and count the number of attendees.
Attendance Tracking: Generation of an Excel file containing the recognized faces as the presence of students.


