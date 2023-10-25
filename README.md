**Description**

We have proposed a vulnerability detection system from java source code using hybrid feature extraction using deep learning and quantum convolutional neural network with self-attentive pooling. 
The open source quantum pennyLane is used to conduct the quantum mechanism. The proposed system addresses a range of vulnerabilities, including improper input validation, 
missing authorizations, buffer overflow attacks, cross-site scripting attacks, and SQL injection attacks that are listed among the most impactful vulnerabilities
by Common Weakness Enumeration (CWE).
**Dataset**
The dataset used is given below
https://samate.nist.gov/SARD/test-cases/search?language%5B%5D=java
**Detail**
Using pennyLane it can be setup as  
import pennylane as qml
dev = qml.device('cirq.simulator', wires=2)
Similarly we need to set up the below requirements for implementing python
Anaconda
Jupitor Notebook 
Keras
and Tensorflow
using Windows-based computer equipped with an Intel® Core™ i7-10700H processor and 128 GB of RAM



