# DDoS-Attack-Detection-using-Machine-Learning
Built a real-time detection system using Random Forest and SVM classifiers on the ISCXIDS2012 dataset. Achieved 97% accuracy by engineering features from network traffic logs and developing an end-to-end pipeline for live malicious traffic classification.
Overview
A Distributed Denial-of-Service (DDoS) attack is a malicious attempt to disrupt the normal traffic of a server, service, or network by overwhelming it with a flood of traffic from multiple sources. These attacks are often launched using compromised devices, including IoT systems, and can severely degrade or crash the target infrastructure. Due to their ability to mimic legitimate traffic, mitigating DDoS attacks is particularly challenging and time-sensitive.

Motivation
For mission-critical applications and enterprises operating at the edge, DDoS mitigation is essential to ensure high availability and service continuity. Software-Defined Networking (SDN) provides a flexible and programmable approach to managing network resources but also introduces new security challenges. DDoS attacks targeting SDN environments, especially data centers, pose significant threats that require advanced detection and response mechanisms.

Objectives
Simulate a network environment using Mininet and Ryu Controller

Generate traffic datasets including DDoS attack patterns

Apply Random Forest (and optionally SVM) machine learning algorithms to detect DDoS attacks

Integrate a basic mitigation module for real-time response to detected attacks

