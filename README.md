# Network_Intrusion_Detection_System
computer networks and the number of applications running on them continue to grow rapidly, network security is becoming increasingly crucial. All computer systems are susceptible to security vulnerabilities, which can be technically challenging and financially burdensome for manufacturers to address. Consequently, the role of Intrusion Detection Systems (IDSs), specialized devices designed to detect anomalies and attacks within networks, has gained significant importance.

For a long time, research in the field of intrusion detection has primarily focused on anomaly-based and misuse-based detection techniques. While misuse-based detection is generally preferred in commercial products due to its predictability and high accuracy, academic research typically views anomaly detection as a more powerful method due to its theoretical potential for addressing novel attacks.

Upon conducting a thorough analysis of recent research trends in anomaly detection, one encounters several machine learning methods reported to achieve very high detection rates of 98% while maintaining a low false alarm rate of 1%. However, when examining state-of-the-art IDS solutions and commercial tools, there is no evidence of using anomaly detection approaches, and practitioners still consider it an immature technology. To uncover the reason behind this contrast, extensive research has been conducted in anomaly detection, considering various aspects such as learning and detection approaches, training datasets, testing datasets, and evaluation methods.

# KeyFeatures
- Real-time Network Traffic Monitoring: The system continuously monitors network traffic, capturing and analyzing packet data in real-time.
- Anomaly Detection: Employs machine learning algorithms to identify anomalous patterns and behavior that deviate from normal network activities, potentially indicating security threats or intrusions.
- Misuse Detection: Utilizes signatures and predefined rules to detect known attack patterns and malicious activities.
- Alert Generation: Generates alerts and notifications for detected threats, enabling prompt investigation and response by security personnel.
- Scalability: Designed to handle large volumes of network traffic and adapt to evolving network environments.
- Customization: Allows for customization of detection rules, algorithms, and thresholds based on specific network requirements and security policies.

# ProblemStatment

The task is to build network intrusion detection system to detect anamolies and attacks in the network. There are two problems.

- Binomial Classification: Activity is normal or attack
- Multinomial classification: Activity is normal or DOS or PROBE or R2L or U2R

# DataSet

The project utilizes the KDD Cup 1999 Data, a dataset containing simulated network traffic and intrusions in a military network environment, to train and evaluate machine learning models for network intrusion detection. The dataset consists of labeled connections with various attack types, allowing for anomaly and misuse detection.

For more about the data: https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection
