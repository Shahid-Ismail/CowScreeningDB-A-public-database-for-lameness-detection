# CowScreeningDB
A public benchmark database for lameness detection in dairy cows
# Introduction

https://user-images.githubusercontent.com/121656894/216747515-6f954085-250d-4be9-b8ef-f71ec4098a83.mp4


# Article
Shahid Ismail, Moises Diaz, Cristina Carmona-Duarte, Jose Manuel Vilar and Miguel A. Ferrer. “CowScreeningDB: A public benchmark dataset for lameness detection in dairy cows”. Computers and Electronics in Agriculture. Under review.
# Instructions for downloading: CowScreeningDB
1. Download the license agreement [CowScreeningDB_License.pdf](https://github.com/Shahid-Ismail/CowScreeningDB-A-public-database-for-lameness-detection/blob/main/CowScreeningDB_License.pdf). Send a scanned copy of license after filling necessary information to xxxx@ulpgc.es. Email should include the following\
Subject: [DATABASE download: CowScreeningDB]\
Body: Your name, e-mail, telephone number, organization, postal mail, purpose for which you will use the database, time and date at which you sent the email with the signed license agreement.
2. Once the email copy of the license agreement has been received at **https://www.ulpgc.es**, you will receive an email with a password. This password can be used to extract the database [CowScreeningDB-Dataset v1.0.zip](https://github.com/Shahid-Ismail/CowScreeningDB-A-public-database-for-lameness-detection/blob/main/CowScreeningDB-Dataset%20v1.0.zip).
# Description of CowScreeningDB
CowScreeningDB is arranged in form of folders which are comma separated values(CSV) files. The structure of CowScreeningDB is given below<br>
![CowScreeningDB_GitHub](https://github.com/Shahid-Ismail/CowScreeningDB-A-public-database-for-lameness-detection/blob/main/CowScreeningDB_GitHub.svg)

Folder name (**05371_1**) contains number assigned to a cow (**05371**) and its illness level (**1**). Similarly, **Illnessdegree_1_Leg_rearleft_Acquisitiondata_15_05_2022_Acquisitiontime_11_14_57.csv** refers to sample which was acquired on **15 May 2022** at **11:14:57** when sensor was attached to rearleft of the leg of a healthy cow (**illness level 1**). 

# Instructions for downlaoding code
1. Down and extract [CowScreeningDB-Classification Algorithm v1.0.zip](https://github.com/Shahid-Ismail/CowScreeningDB-A-public-database-for-lameness-detection/blob/main/CowScreeningDB-Classification%20Algorithm%20v1.0.zip)
2. **Structure_Generator.m** generates File, Segment and Experiment names.
3. **Features_Generator.m** generates the features for a signal.
4. **SVM_Training_All_Features.m, SVM_Training_Features_Abalation_Study.m and SVM_Training_Chanels_Abalation_Study.m** generates the results for the complete study and ablation studies based on features/ channels<br>
![CowScreeningDB_SVM_GitHub](https://github.com/Shahid-Ismail/CowScreeningDB-A-public-database-for-lameness-detection/blob/main/CowScreeningDB_SVM_GitHub.svg)

# Results
Figure shows the area under the curve (AUC) for a study involving all features\
<img src="https://user-images.githubusercontent.com/121656894/210492661-3c20471d-b830-47da-85c8-1c765926813a.png" height="450" width="600">
