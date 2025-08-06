# DDoS-Attack-Detection-using-Machine-Learning

Built a real-time detection system using Random Forest and SVM classifiers on the ISCXIDS2012 dataset. Achieved 97% accuracy by engineering features from network traffic logs and developing an end-to-end pipeline for live malicious traffic classification.
Overview
A Distributed Denial-of-Service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a server, service, or network by overwhelming it with a flood of traffic from multiple sources. These attacks are often launched using compromised devices, including IoT systems, and can severely degrade or crash the target infrastructure. Due to their ability to mimic legitimate traffic, mitigating DDoS attacks is particularly challenging and time-sensitive.

Motivation

For mission-critical applications and enterprises operating at the edge, DDoS mitigation is essential to ensure high availability and service continuity. Software-Defined Networking (SDN) provides a flexible and programmable approach to managing network resources but also introduces new security challenges. DDoS attacks targeting SDN environments, especially data centers, pose significant threats that require advanced detection and response mechanisms.

🛠️ How to Run This Project

Step 1: Download the ISCXIDS2012 dataset from here:
https://www.unb.ca/cic/datasets/ids.html

Step 2: Install Mininet using the official instructions:
https://github.com/mininet/mininet#installation

Step 3: Install the Ryu SDN controller from the official GitHub:
https://github.com/faucetsdn/ryu#installation

Step 4: Clone this GitHub repository and open the Jupyter notebook.

Step 5: Run all cells in the notebook to preprocess the data and train the model (Random Forest or SVM).

Step 6: After training, the real-time detection module can be tested with simulated traffic via Mininet.

Step 7: The trained model classifies traffic as normal or DDoS in real time.


pip install pandas numpy matplotlib
