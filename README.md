# qml-ddos
Code related to the research work:
## “Benchmarking quantum machine learning for detecting DDoS cyber-attacks: a NISQ-era evaluation”  
**Ricardo S. Alonso, Guillermo Rivas, Rodrigo Gil-Merino, Diego Valdeolmillos, Javier Prieto**
## Abstract
The Internet of Things (IoT) connects billions of resource-constrained devices that are susceptible to *botnet* infections and exploitation in *Distributed Denial of Service* (DDoS) attacks. Although classical machine learning (ML) methods can detect such threats, the practical potential of *Quantum Machine Learning* (QML) for this task remains largely unexplored under controlled experimental conditions. This work presents a systematic benchmarking study comparing classical and quantum supervised learning models for DDoS attack detection using the `CICDDoS2019` dataset. On the classical side, *Support Vector Machines* (SVMs) and *Artificial Neural Networks* (ANNs) are evaluated. On the quantum side, *Quantum Support Vector Machines* (QSVMs) with three different quantum kernels and *Quantum Neural Networks* (QNNs) with three feature maps (*angle embedding*, *amplitude embedding*, *ZZ feature map*) and two variational forms (*two-local*, *tree tensor*) are systematically compared. Experimental results show that, in the current Noisy Intermediate-Scale Quantum (NISQ) era, classical models match or outperform their quantum counterparts. Among quantum approaches, QSVMs outperform QNNs, and *angle embedding* consistently yields the highest *f1-score* across all quantum models. A key finding is that QNN performance depends primarily on the feature map rather than the variational circuit architecture. These results provide an honest baseline for future QML research in cybersecurity and highlight both the current limitations and the design choices that most influence quantum model effectiveness.
## Keywords
*Internet of Things*, *Distributed Denial of Service*, *quantum machine learning*, *quantum support vector machines*, *quantum neural networks*, *NISQ*, *benchmarking*  
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
