# qml-ddos
Code related to the Master's Thesis:  
## “Quantum Machine Learning for detection of DDoS cyberattacks”  
**Master's Degree in Quantum Computing, International University of La Rioja (UNIR)**  
**presented by** Ricardo S. Alonso Rincón  
**supervised by** Dr. Rodrigo Gil-Merino y Rubio  
**co-supervised by** Dr. Javier Prieto Tejedor  
## Abstract
In the Internet of Things (IoT), devices have limited computational capabilities in order to reduce their size and energy consumption, making them vulnerable to the deployment of *botnets* and their use in *Distributed Denial of Service* (DDoS) cyberattacks on remote servers, which limits the services available to legitimate users and causes economic losses. Although classical *Deep Learning* techniques can detect these cyberattacks, they require large amounts of data and computational resources. *Quantum Machine Learning* emerges as a potential solution for solving problems more energy-efficiently. This work compares various classical learning models —*Support Vector Machines* (SVM) and *Artificial Neural Networks* (ANN)— and quantum models —*Quantum Support Vector Machines* (QSVM) and *Quantum Neural Networks* (QNN)— using different *feature maps* to encode classical data and detect DDoS attacks from TCP/IP packet flows. The results show that QSVMs achieve an *f1-score* close to classical models, with 
*angle embedding* being the best feature map for both QSVMs and QNNs, although it requires longer computation time due to slower convergence.  
## Keywords
*Internet of Things*, *DDoS cyberattacks*, *quantum machine learning*, *quantum support vector machines*, *quantum neural networks*.  
## Main references related to data, methodology and code used in this work
Combarro, E. F., González-Castillo, S., & Di Meglio, A. (2023). *A Practical Guide to Quantum Machine Learning and Quantum Optimization: Hands-on Approach to Modern Quantum Algorithms*. Packt Publishing Ltd.

Dasari, K. B., & Devarakonda, N. (2022). Detection of TCP-based DDoS attacks with SVM classification with different kernel functions using common uncorrelated feature subsets. *International Journal of Safety and Security Engineering, 12*(2), 239-249.

Hadi, H. J., Hayat, U., Musthaq, N., Hussain, F. B., & Cao, Y. (2022, November). Developing Realistic Distributed Denial of Service (DDoS) Dataset for Machine Learning-based Intrusion Detection System. In *2022 9th International Conference on Internet of Things: Systems, Management and Security (IOTSMS)* (pp. 1-6). IEEE.
