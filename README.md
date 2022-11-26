Classification Of Plasmodium Species From Thin Smear Images Using Deep Learning For Early Malaria Diagnosis


ABSTRACT 

Plasmodium detection automation program from blood smear images using deep learning has been developed to support malaria diagnosis. Early research has only been focused on the positive and negative result of Plasmodium from blood smear images, then in its development, the result of PlasmodiumVF-Net research can detect Plasmodium falciparum and Plasmodium vivax in thick blood smear. At the same time, YOLOV3 and YOLOV4 methods has also been used to detect Plasmodium falciparum. This research used YOLOV5 (You Only Look Once) method to detect 5 species of Plasmodium that are known to cause malaria; P. Falciparum, P. Knowlesi, P. Malariae, P. Ovale, dan P. Vivax. The classification of Plasmodium species is crucial to determine prognosis and treatment for Malaria patients. 103 blood smear images of Malaria patients from the image gallery of Centers for Disease Control and Prevention were used as a dataset, it consists of 26 images positive for P. Falciparum, 15 images positive for P. Knowlesi, 23 images positive for P. Malariae, 19 images positive for P. Ovale, dan 24 images positive for P. Vivax. In the YOLOV5 object detection method, 5 models were tested in this research; yolov5l, yolov5m, yolov5m, yolov5n, yolov5s, and yolov5x, to determine the best model. Yolov5m model is proven to be the best model to detect 5 species of Plasmodium with mAP of 0.975, time inference of 0.017 s, accuracy of 0.78, precision of 0.93, recall of 0.82, specificity of 0.99, and AUC of 0.9. Characterized by the AUC score, this model is classified as excellent. 

Keywords – Malaria, Plasmodium, Deep Learning, You Only Look Once, YOLOV5  

 
INTRODUCTION 

Malaria is ranked within the top 10 types of diseases that causes death in the world and, based on data from The World Malaria Report, there was a spike in cases in 2020, which amounted to a total of 241 million malaria cases compared to the 227 million malaria cases that occurred in 2019. It is estimated that the number of deaths due to malaria reached 627,000 cases (WHO, 2021). Microscope images test with blood smear is the gold standard method in malaria diagnosis (Endeshaw, et al., 2008). To overcome the weaknesses of manual examination, several studies have been conducted to automate Plasmodium detection in blood smear images. Early research only focused on the results of positive and negative Plasmodium from blood smear images (Quinn, et al, 2013). The results of PlasmodiumVF-Net research were able to detect Plasmodium falciparum and Plasmodium vivax on thick blood smears (Kassim, et al, 2021). Meanwhile, the YOLOV3 and YOLOV4 methods have been used to detect Plasmodium falciparum (Abdurrahman, et al, 2021). Our product is a Plasmodium detection automation program from thin blood smear images that is able to detect 5 Plasmodium species (P. Falciparum, P. Knowlesi, P. Malariae, P. Ovale, and P. Vivax) with excellent mAP (mean Average Precision), time inference, accuracy, precision, recall, specificity, and AUC (Area Under Curve) score. The classification of Plasmodium species is important because it determines the prognosis and treatment of malaria patients. This program is built using the YOLOV5 deep learning method. 

 
OBJECTIVE 

The purpose of the research is to develop a program based on deep learning utilizing object detection method using You Look Only Once (YOLO) Version 5. Furthermore, the program will be used to identify 5 Plasmodium species in thin blood smear images. 


DESCRIPTION OF THE PRODUCT 

The end product of the research is a program, capable of detecting several Plasmodium species through thin blood smear. Program is built in Google Collaboratory from Google with Phyton as a programming language. 103 blood smear images of Malaria patients were used as a dataset from the image gallery provided by Centers of Disease Control and Prevention. Dataset is then annotated using Roboflow framework equipped with 5 classes; label falciparum, knowlesi, malariae, vivax and ovale. These 5 classes represent Plasmodium species able to cause malaria in humans. The deep learning method used is You Look Only Once (YOLO) version 5 or YOLO5. This research is conducted to find the best YOLOV5 model with the parameters of mAP, time inference, accuracy, precision, recall, specificity, and AUC. Comparation of different models of YOLOV5 in object detection is shown in the table below (Table 1). Based on the comparation table below, it is determined that yolov5m is the best YOLOV5 model for this research. The result of the Plasmodium species classification program is a confusion matrix along with detection result image shown below. 

NOVELTY 

In this research, program development is done in order to identify different species of Plasmodium-causing Malaria to help healthcare workers diagnose 5 infectious malaria species (P. Falciparum, P. Knowlesi, P. Malariae, P. Ovale, dan P. Vivax) with good mAP, time inference, accuracy, precision, recall, specificity and AUC score. YOLOV5 deep learning method is used in contrast to previous research that uses YOLOV4 (Kassim, et al., 2021). Program development is made with the hopes of the end product being compatible and updateable. 

CONCLUSION 

The product built is an early detection program to identify Plasmodium species that causes malaria using a database of microscope preparation images from patient's blood. The results showed that the object detection method using YOLO version 5 is able to classify thin blood smear images into 5 Plasmodium species. The product produces an mAP score of 0.975, time inference of 0.017 s, accuracy of 0.78, precision of 0.93, recall of 0.82, specificity of 0.99, and AUC of 0.9. Based on the AUC score, the model built is classified as an excellent classification. 
