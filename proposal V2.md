# Proposal V2

## Introduction

Deep Learning methods are currently state-of-the-art in many computer vision and image processing problems. After years of intensive investigation, a few models matured and became important tools, including Convolutional Neural Networks (CNNs), Siamese and Triplet Networks, Auto-Encoders (AEs), and Generative Adversarial Networks (GANs). The field is fast-paced and there are a lot of terminologies to catch up with for those who want to adventure in deep learning waters.

Over recent years, deep learning methods have been shown to outperform previous state-of-the-art machine learning techniques in several fields, with computer vision being one of the most prominent examples.

As one of the most successful applications of image analysis and understanding, face recognition has recently received significant attention, especially during the past several years. Even though current machine recognition systems have reached a certain level of maturity, their success is limited by the conditions imposed by many real applications. For example, face recognition in an outdoor environment with changes in illumination and/or pose remains a largely unsolved problem. In other words, current systems are still far away from the capability of the human perception system.

Face Recognition is a technology capable of identifying or verifying a person’s face from an image or video. It uses biometrics to map facial features from an image or video. It can help verify the personal identity of a person by looking at their faces. Face recognition has these features, and obviously, it can help people verify attendance. In today’s digital age, face recognition is very helpful in this area. especially for educational areas that require attendance verification. Maybe some parts are now relying on technology to verify attendance. But some still use traditional methods that take a long time. Therefore, face recognition is very helpful in terms of verifying attendance and speeds up the process of recording and verifying the person.

It is based on the truth that a considerable number of students register others’ attendance, which has become a common phenomenon. The efficiency of attendance checks by manual record is not always satisfying, and it is really a headache for the whole educational field. 

In the proposed system, initially, all the students will be enrolled by storing their facial images with a unique ID. At the time of attendance, real-time images will be captured and the faces in those images will be matched with the faces in the pretrained dataset. 
The best match results in displaying the name & roll number of that student. Attendance of the student is automatically updated in the excel sheet.


## Problem Statment

Attendance recording of a student in an academic organization plays a vital role in judging a student’s performance. Manual labor involved in this process is time-consuming and is only available for a classroom in a university with around 80 students. Traditional methods of automatic attendance systems like fingerprints, RFIDs, or IRIS scans are easy to bypass as the biometric features such systems take into consideration are far less than facial features. An automated attendance management system based on face detection and face recognition techniques is proposed.

In order to improve the efficiency of management and enhance the atmosphere of learning, in this project, Developing an attendance system based on face recognition and image processing is a must. Our facial recognition system is used to detect a person’s face and then compare it with the stored facial database to recognize it. Once the face is recognized, his attendance is marked and stored in a database.



## Objectives

- To understand deep learning and computer vision concepts.
- To implement those concepts in a classroom attendance project.



## Project Scope (Limitations)

- Initially, in one classroom.
- There should be a PC with a local database of students' images in the classroom. 
- Number of students in the classroom is ## at max.   (based on the detection algorithm)
- High-resolution camera.
- Camera accesses a good and clear vision. 
- Students wearing masks will not be assigned as attended.
- No distinguishing between identical twins.
