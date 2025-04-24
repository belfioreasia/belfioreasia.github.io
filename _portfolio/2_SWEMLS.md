---
title: "Aki Predictor"
excerpt: "A Machine Learning model for the diagnosis of Acute Kidney Injury (AKI). Submitted as coursework for the 'Software Engineering for ML Systems' postgraduate course at Imperial College London. <br/><img src='/images/aki-system.png'>"
collection: portfolio
---

Many serious medical conditions can result in kidney injury, making kidney function a good, if lagging, indicator of general health.
Acute kidney injury is generally detected through the presence of creatine, a waste product, in the blood. If a patient’s kidneys are damaged, they will not be able to remove creatinine effectively, leading to an increased amount being found in blood tests.

ML Model
===

This is a proposed Machine Learning model for the prediction of Acute Kidney Injury (AKI) from clinical temporal changes of creatinine levels.
Trained on 7000+ clinical samples, this ML model can correctly predict the presence of AKI with >98% accuracy.

[<kbd>Code Implemetation</kbd>](https://github.com/belfioreasia/aki-predictor)


Full System
===
A real-time prediction system to detect Acute Kidney Injury (AKI) from clinical temporal changes of creatinine levels using a Machine Learning model.

The System processes real-time *Health Level 7* (HL7) messages sent from the Hospital's Clinical Systems: *Patient Administration System* (PAS) and *Laboratory Information Management System* (LISM).
For every new blood test result, the system will run the prediction using the pre-trained model and, if AKI is detected, the system will page the Hospital's Clinical Response team in less than 3 seconds from the test result receipt.

All patient data from the Hospital is stored in a database, with separate tables for Patient Data and Blood Test Results data.

![alt text](/images/aki-system.png)

View on [<kbd>Github</kbd>](https://github.com/belfioreasia/swemls-aki-prediction) or [<kbd>GitLab</kbd>](https://gitlab.doc.ic.ac.uk/ab6124/swemls_aki3).