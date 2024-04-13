# Security-Surveillance-System

![Security Surveillance System](https://media1.tenor.com/images/c6b89cb68c230e204ab7665b3a3616da/tenor.gif?itemid=3471448)

Welcome to our innovative Security Surveillance System project!

## Overview

Our Security Surveillance System combines advanced face recognition and action recognition models to create a comprehensive solution for monitoring and detecting intrusions. Leveraging state-of-the-art deep learning techniques and MediaPipe library, our system can accurately identify faces and detect various actions such as walking, standing, running, and waving.

## Features

- **Face Recognition:** Our face recognition model achieves high accuracy in identifying faces, even under challenging conditions such as varying lighting and facial expressions.
- **Action Recognition:** Using MediaPipe and machine learning algorithms, our system can detect various actions performed by individuals, allowing for enhanced surveillance capabilities.
- **Integration with Twilio API:** In addition to facial and action recognition, our system integrates with the Twilio API to send notifications to system owners in case of intrusion detection.
- **Smart Surveillance:** Our system intelligently detects intrusions, captures images of the intruder, and sends notifications to the system owner, providing real-time monitoring and security.

## Usage

To utilize our Security Surveillance System, follow these steps:

1. **Download Models:** Download the pre-trained face recognition and action recognition models from the following links and save them in Model directory:
   - [Face Recognition Model](https://drive.google.com/drive/folders/14BPBpt61YAgJzOom9dcRg15XuFgucth3?usp=sharing)
   - [Action Recognition Model](https://drive.google.com/drive/folders/14BPBpt61YAgJzOom9dcRg15XuFgucth3?usp=sharing)

2.  **Configure Twilio:** Create your account in twilio and save credential in credential.txt file


3. **Integration:** Integrate the downloaded models into your system and configure the Twilio API for notifications.


4. **Surveillance:** Deploy the system in your desired environment and start monitoring for intrusions.


5. **Enjoy:** Experience enhanced security and peace of mind with our Security Surveillance System!

## Algorithm used: 
this project uses **Convolutional neural network** for face recognition and also for actionr recognition. while developing that model we faced **major issue** which was related to **recognising unknown** and **known faces** means **differentiating** between them that issue i faced.so to overcome that issue we used LBWH recogniser which is the library of cv2 we used it's confidence value as a differentiating factor if the confidence value is above 90 then we can call the face is not authorised but if the face is below **90** then we can assume it as the accurate prediction. 


## Contribution

We welcome contributions from the community to further enhance and refine our Security Surveillance System. Whether it's improving model accuracy, adding new features, or optimizing performance, your contributions are valuable to us.

## Contact

For inquiries or support regarding our Security Surveillance System, please contact us at [sairajrajput6@gmail.com].

---

