# PPE Safety Goggles Compliance Demo > Version 8 PPE Safety Goggles Detection
https://universe.roboflow.com/kathy-portfolio/ppe-safety-goggles-compliance-demo-8hm10

Provided by a Roboflow user
License: CC BY 4.0

**Project Overview: Lab PPE Goggles Detection**

**Goal**
This project aims to automate the detection and compliance verification of safety goggles as part of Personal Protective Equipment (PPE) in laboratory environments. By leveraging deep learning object detection, the workflow identifies whether individuals are wearing the required PPE goggles, helping organizations improve workplace safety and adhere to lab safety protocols.

**Key Features**
* Automated Goggles Detection: Utilizes a custom-trained object detection model to locate and identify safety goggles in photos or video frames from lab settings.
* High Accuracy: The model has been fine-tuned to recognize “Goggles” instances with high confidence, minimizing false positives and negatives.
* Real-Time and Batch Processing: The workflow supports both single-image and batch/image stream inference for flexible deployment in various environments (camera feeds, compliance audits, etc).
* Predictions Visualization: The pipeline provides visual outputs with bounding boxes and labels for each detected goggles instance, enabling quick visual verification.
* Compliance Reporting: Includes a step that counts the number of detected goggles, which can be exported for safety records, compliance dashboards, or integration with automated gatekeeping systems.

**Workflow Structure**
* Input Image Ingestion: The workflow starts with an image input, either from a camera or upload.
* Object Detection: Images are passed through a custom Roboflow object detection model trained specifically for goggles detection.
* Bounding Box Visualization: Detected instances are displayed with bounding boxes for clear onscreen review.
* Label Visualization: Adds labels directly onto the image, complementing the bounding boxes with class names (e.g., "Goggles").
* Counting and Output: The workflow counts the number of detected goggles and provides both the count and annotated image as output.

**Applications**
* Automated Lab Access Control: Prevents entry to controlled areas unless goggles are detected.
* Compliance Documentation: Generates verifiable records of PPE compliance during lab work.
* Safety Auditing: Automates part of the compliance checks during periodic lab audits, reducing manual effort.

**Benefits**
* Enhances lab safety by reducing human oversight.
* Supports faster, objective, and scalable compliance verification.
* Provides an audit trail for safety records and reporting.