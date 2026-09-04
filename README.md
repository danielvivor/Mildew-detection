# Mildew Detection in Cherry Leaves

The Mildew Detection in Cherry leaves application is a Machine Learning tool built with Streamlit to visually detect powdery mildew in cherry tree leaf samples. It aims to streamline crop inspection for Farmy & Foods by reducing manual verification time.

## Business Requirements
1. **Requirement 1:** The client is interested in conducting a study to visually differentiate a cherry leaf that is healthy from one that contains powdery mildew.
2. **Requirement 2:** The client is interested in predicting if a cherry tree leaf is healthy or contains powdery mildew.

## User Stories & ML Mapping
- **User Story 1:** As a client, I want to view average image characteristics and variability for healthy vs. infected leaves so that I can visually distinguish between them.
- **User Story 2:** As a client, I want to upload an image of a cherry leaf to predict instantly whether it is healthy or infected with powdery mildew.
- **User Story 3:** As an analyst, I want to view the ML model performance metrics (loss/accuracy) so that I can trust its predictions.

## ML Business Case
- **Goal:** Predict whether a given cherry leaf image is healthy or infected with powdery mildew.
- **Learning Method:** Binary Classification (Supervised Learning using a Convolutional Neural Network).
- **Ideal Outcome:** An automated, scalable system that replaces 30-minute manual tree inspections with instant digital predictions.
- **Success Criteria:** Achieve at least **90% accuracy** on the test dataset.
- **Output:** Categorical label (`Healthy` or `Powdery Mildew`) along with prediction probability.

## Dashboard Design
- **Page 1: Quick Summary** - Project background and business requirements.
- **Page 2: Leaf Visualizer** - Visual differences, average/variability images, and image montages.
- **Page 3: Mildew Detector** - Image uploader and real-time prediction output.
- **Page 4: Hypotheses & Validation** - Key hypotheses regarding leaf visual signatures.
- **Page 5: ML Performance** - Model training metrics and evaluation plots.
