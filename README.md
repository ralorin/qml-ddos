# qml-ddos
Code related to the research work:
## “Quantum machine learning for detection of DDoS cyberattacks”  
**Ricardo S. Alonso, Guillermo Rivas, Rodrigo Gil-Merino, Diego Valdeolmillos, Javier Prieto**
## Abstract
In the Internet of Things (IoT), devices are designed with constrained computational capacity to minimize size and energy consumption, which renders them susceptible to *botnet* infections and their exploitation in *Distributed Denial of Service* (DDoS) attacks against remote servers. Such attacks degrade service availability for legitimate users and cause substantial economic losses. Although conventional *Deep Learning* methods can detect these threats, they typically require extensive data and significant computational resources. *Quantum Machine Learning* (QML) has emerged as a promising alternative, offering improved energy efficiency. This work investigates the application of *Quantum Neural Networks* (QNNs) with different *feature maps* for encoding classical TCP/IP traffic data to detect DDoS attacks. The performance of QNNs is compared against classical models —*Support Vector Machines* (SVMs) and *Artificial Neural Networks* (ANNs)— and quantum models such as *Quantum Support Vector Machines* (QSVMs). Experimental results show that QSVMs outperform QNNs and deliver an *f1-score* comparable to classical approaches. Among the evaluated feature maps, *angle embedding* provides the highest performance in both QSVMs and QNNs, albeit at the cost of longer training times due to slower convergence.
## Keywords
*Internet of Things*, *Distributed Denial of Service*, *quantum machine learning*, *quantum support vector machines*, *quantum neural networks*.  
## Main references related to data, methodology and code used in this work
Combarro, E. F., González-Castillo, S., & Di Meglio, A. (2023). *A Practical Guide to Quantum Machine Learning and Quantum Optimization: Hands-on Approach to Modern Quantum Algorithms*. Packt Publishing Ltd.

Dasari, K. B., & Devarakonda, N. (2022). Detection of TCP-based DDoS attacks with SVM classification with different kernel functions using common uncorrelated feature subsets. *International Journal of Safety and Security Engineering, 12*(2), 239-249.

Hadi, H. J., Hayat, U., Musthaq, N., Hussain, F. B., & Cao, Y. (2022, November). Developing Realistic Distributed Denial of Service (DDoS) Dataset for Machine Learning-based Intrusion Detection System. In *2022 9th International Conference on Internet of Things: Systems, Management and Security (IOTSMS)* (pp. 1-6). IEEE. 
## Dataset
The `CICDDDoS2019` dataset created by Hadi et al. (2022) and used in this work can be obtained through the following URL address where it is described and can be downloaded:  
[https://www.unb.ca/cic/datasets/ddos-2019.html](https://www.unb.ca/cic/datasets/ddos-2019.html)
## Note on Master's Thesis
This work is originally based on the Master’s Thesis:  
  
**“Quantum Machine Learning for detection of DDoS cyberattacks”**  
**Master’s Degree in Quantum Computing, International University of La Rioja (UNIR), Spain**  
**presented by** Dr. Ricardo S. Alonso Rincón  
**supervised by** Dr. Rodrigo Gil-Merino y Rubio  
**co-supervised by** Dr. Javier Prieto Tejedor  
