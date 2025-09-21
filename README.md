# roboflow-object-detection PPE safety goggles compliance

🥽 PPE Goggle Detection with Roboflow (RF-DETR Nano)

***Problem***

Ensuring compliance with personal protective equipment (PPE) in laboratory environments is critical for worker safety. Manual monitoring of goggle use is time-consuming, inconsistent, and prone to error. Automating this process with computer vision can improve compliance tracking and reduce safety risks.

***Method***

Data Annotation: Collected and labeled lab images in Roboflow, focusing on the presence or absence of safety goggles.

Dataset Preparation: Applied a 70/20/10 split for training, validation, and testing.

Model Selection: Trained an object detection model using RF-DETR (Nano) in Roboflow.

Workflow: Ran multiple training iterations in Roboflow, reviewed accuracy metrics, and adjusted confidence thresholds to refine detection performance.

***Current Results***

The initial model demonstrates baseline accuracy in detecting goggles within lab images.
This repository includes screenshots of:

Annotation interface (manual goggle labeling).

Training and test workflow results.

Sample detection outputs (bounding boxes identifying goggles).

***Business Impact***

This project demonstrates hands-on experience in computer vision workflows applied to lab safety compliance. Once optimized, the model could:

Automate PPE monitoring in labs and manufacturing facilities.

Support compliance audits and safety reporting.

Reduce manual supervision while improving accuracy and consistency.

***Next Steps***

Expand dataset with more diverse lab images, lighting conditions, and angles.

Tune hyperparameters to improve precision/recall for goggle detection.

Deploy as a Streamlit web app for real-time PPE monitoring.

***Tools & Skills Demonstrated***

Roboflow – dataset annotation and training

RF-DETR (Nano) – object detection model architecture

Python – workflow integration and analysis

Computer Vision – data labeling, model training, and evaluation

Streamlit (planned) – deployment for real-time detection


link to the project: https://universe.roboflow.com/kathy-portfolio/ppe-safety-goggles-compliance-demo-8hm10