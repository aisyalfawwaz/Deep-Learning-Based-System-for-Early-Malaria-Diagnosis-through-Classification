

# README

"This research project was awarded the Gold Medal at the Negeri Sembilan International Exposition (NSIEx) 2022, in recognition of its outstanding contributions to the field. We are honored to receive this prestigious award and grateful for the opportunity to showcase our research at this international event."

<h2>🚀 Demo</h2>

[https://www.youtube.com/watch?v=eBggPVWZ5OM](https://www.youtube.com/watch?v=eBggPVWZ5OM)

## Introduction

Malaria is an acute infectious disease caused by protozoa from the Plasmodium genus, which is transmitted to humans through the bite of infected female Anopheles mosquitoes. It is one of the major health problems that cause death in high-risk groups such as infants, toddlers, and pregnant women. Malaria is ranked among the top 10 diseases causing death globally, with Indonesia being the second highest country in terms of the number of cases of malaria in Southeast Asia. The lack of early detection contributes to high mortality rates in malaria cases. 

Currently, various methods are available to detect Plasmodium parasites, including real-time Polymerase Chain Reaction (PCR), Rapid Diagnostic Tests (RDTs), and microscope image tests using blood smears. Among these methods, the microscope image test with blood smear is a fast and accurate method that can be applied in health care facilities around the community. However, the analysis method is still performed manually in health facilities in Indonesia, which results in an ineffective and inefficient diagnosis process. 

To address this issue, a prototype is developed that can assist healthcare workers in diagnosing malaria species with high specificity, sensitivity, and real-time capability. This research aims to classify Plasmodium species from thin smear images using deep learning YOLOV5 and Framework Roboflow utility for early malaria diagnosis. 

## Methods

The research method consists of information and data gathering, data processing, and evaluating results. Information is collected through literature studies to increase knowledge related to the problem. Data is obtained from the Center for Disease Control and Prevention, which contains 103 red blood cell images of malaria patients. This dataset consists of 26 positive images of P. Falciperum, 15 positive images of P. Knowlesi, 23 positive images of P. Malariae, 19 positive images of P. Ovale, and 24 positive images of P. Vivax. 

Data processing begins with image annotation using the Roboflow framework, which creates five classes consisting of falciparum, knowlesi, malariae, vivax, and ovale labels. The annotated dataset is divided into 88% training data, 8% validation data, and 4% testing data. The detection program with YOLOV5 is built using the Google Collaboratory framework and the Python programming language. The yolov5 detection program has several models, which are l, m, n, s, and x models. This program is run for each yolov5 model. 

Evaluation is conducted to determine which model is the most effective for plasmodium detection by comparing the values of mAP, time inference, and other performance metrics. 

## Conclusion

This research presents a prototype that can assist healthcare workers in diagnosing Plasmodium species with high specificity, sensitivity, and real-time capability. By using deep learning YOLOV5 and Framework Roboflow utility, the classification of Plasmodium species from thin smear images can be performed automatically. The results of this research can contribute to the development of a more efficient and effective malaria diagnosis process. 

## References

- Berzosa, P., de Lucio, A., Romay-Barja, M., Herrador, Z., Gonzalez, V., Garcia, L., Fernández-Martínez, A., Santana-Morales, M. A., & Valladares, B. (2018). Comparison of three diagnostic methods (microscopy, RDT, and PCR) for the detection of malaria parasites in representative samples from Equatorial Guinea. Malaria Journal, 17(1), 333. https://doi.org/10.1186/s12936-018-2489-9
- Fitriany, Julia., Sabiq, Ahmad. (2018). Malaria. Jurnal Averrous Vol. 4, No. 2, 1-2. 
- Gebrekidan, L. D., & Hiruy, H. N. (2019). Assessment of malaria microscopic diagnosis performance of laboratory professionals in Addis Ababa’s Public Health Facilities. Training, 5(93), 44-08. 
- Herlambang, Muhammad Fahmi (2020) TA: Pengenalan Karakter Huruf Braille dengan Metode Convolutional Neural Network. Skripsi thesis, Institut Teknologi Nasional Bandung. 
- Kassim, Y.M., Yang, F., Yu,H., Maude, R.J., Jaeger, S. (2021). Diagnosing Malaria Patients with Plasmodium falciparum and vivax Using Deep Learning for Thick Smear Images. Diagnostics 2021, 11, 1994. https://doi.org/10.3390/diagnostics11111994. 
- Nugroho, H. A., Akbar, S. A., & Murhandarwati, E. E. H. (2015, October). Feature extraction and classification for detection malaria parasites in thin blood smear. In 2015 2nd international conference on information technology, computer, and electrical engineering (ICITACEE) (pp. 197-201). IEEE.  
- Vijayalakshmi, A. (2020). Deep learning approach to detect malaria from microscopic images. Multimedia Tools and Applications, 79(21), 15297-15317. 
- World Health Organization. 2021. World malaria report. Geneva, Switzerland: World Health Organization.  
