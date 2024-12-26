# Complete-ML-Pipeline-MLOps
This project covers the end to end understanding for creating an ML pipeline and working around it using DVC for experiment tracking and data versioning.

### Agenda:

1.	Create an end to end ML pipeline. (Logging Exception etc.)
2.	Automate the pipeline using DVC. (YAML)
3.	Adding configurable params to pipeline
4.	Experiment tracking using dvclive.
5.	AWS setup with DVC for data versioning.

### ML_Pipeline_Architecture:

![ML_Pipeline_Architecture](https://github.com/user-attachments/assets/ff3c271f-da5c-418d-8094-b5efe9a8945d)

## **Logging:**

Logging is essential for tracking the performance, behavior, and issues of machine learning models throughout their lifecycle. 

### 1. What is Logging

**Definition:** Logging refers to the systematic recording of events, metrics, and errors that occur during the development, deployment, and operation of machine learning models.

**Purpose:** It helps in monitoring model performance, diagnosing issues, and ensuring reproducibility in machine learning workflows.

### 2. Why Use Logging

- **Performance Monitoring:** Track how well models perform in production.
- **Error Tracking:** Identify and troubleshoot issues that arise during model training and inference.
- **Audit Trails:** Maintain records of model versions, data changes, and deployment processes for compliance and analysis.
- **Collaboration:** Facilitate communication among team members by providing insights into model behavior.

### 3. Basic Components of Logging

- **Loggers:** Objects that capture log messages.
- **Log Levels:** Different levels of importance for messages (e.g., DEBUG, INFO, WARNING, ERROR, CRITICAL).
- **Handlers:** Outputs for log messages (e.g., console, files, monitoring systems).
- **Formatters:** Define the structure of log messages.

### Logging Levels

- **DEBUG:** Detailed information, typically of interest only when diagnosing problems.
- **INFO:** Confirmation that things are working as expected.
- **WARNING:** An indication that something unexpected happened, or indicative of some problem in the near future.
- **ERROR:** Due to a more serious problem, the software has not been able to perform some function.
- **CRITICAL:** A very serious error, indicating that the program itself may be unable to continue running.

NLTK docs : https://www.nltk.org/index.html

