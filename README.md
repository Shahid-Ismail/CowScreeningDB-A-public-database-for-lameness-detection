# AICow
Complete Artificial Intelligence system for lameness screening in dairy cows
# Article
Shahid Ismail, Moises Diaz, Cristina Carmona, Jose Manuel Vilar Guereno and Miguel Angel Ferrer Ballester
# Instructions for downloading: AICow-Dataset
1. Download the license agreement [AICow License.pdf](https://github.com/Shahid-Ismail/Test/files/10341673/AICow_License.pdf). Send a scanned copy of license after filling necessary information to xxxx@ulpgc.es. Email should include the following\
Subject: [DATABASE download: DeepSignDB]\
Body: Your name, e-mail, telephone number, organization, postal mail, purpose for which you will use the database, time and date at which you sent the email with the signed license agreement.
2. Once the email copy of the license agreement has been received at printf '\e]8;;https://www.ulpgc.es\e\\ulpgs\e]8;;\e\\\n' , you will receive an email with a password. This password can be used to extract the database [AICow-Dataset v1.0.zip](https://github.com/Shahid-Ismail/Test/files/10341674/AICow-Dataset.v1.0.zip).
3. ** ulpgs https://www.ulpgc.es**
# Description of AICow-Dataset
AICow-Dataset is arranged in form of folders which are comma separated values(CSV) files. The structure of AICow-Dataset is given below<br>
![AICow_GitHub](https://user-images.githubusercontent.com/121656894/210198942-e8583512-b5b4-48a0-bb7e-b2dd68beb7a6.svg)\
Folder name (**05371_1**) contains number assigned to a cow (**05371**) and its illness level (**1**). Similarly, **Illnessdegree_1_Leg_rearleft_Acquisitiondata_15_05_2022_Acquisitiontime_11_14_57.csv** refers to sample which was acquired on **15 May 2022** at **11:14:57** when sensor was attached to rearleft of the leg of a healthy cow (**illness level 1**). 

# Instructions for downlaoding: AICow-SVM
1. Down and extract [AICow-Classification Algorithm v1.0.zip](https://github.com/Shahid-Ismail/Test/files/10330214/AICow-Classification.Algorithm.v1.0.zip)
2. **Structure_Generator.m** generates File, Segment and Experiment names.
3. **Features_Generator.m** generates the features for a signal.
4. **SVM_Training_All_Features.m, SVM_Training_Features_Abalation_Study.m and SVM_Training_Chanels_Abalation_Study.m** generates the results for complete study, ablation studies based on features and channels.

![AICow_SVM_GitHub](https://user-images.githubusercontent.com/121656894/210477181-e6d67c51-3015-4e25-a0b6-03e4eb7c328d.svg)

# Results
