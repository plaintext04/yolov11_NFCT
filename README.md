YOLOv11 + Llama-3.2-Vision: Medical Image Detection & Analysis
This project combines the precision of Ultralytics YOLOv11 for object detection with the generative power of Llama-3.2-Vision (VLM) to automate the identification and professional description of lesions in medical imaging (e.g., CT scans).

Features
YOLOv11X Training & Optimization: Supports fine-tuning and transfer learning using the yolo11x.pt model on custom medical datasets.

Two-stage Inference Pipeline:

Stage 1: YOLOv11 detects specific lesions, identifying categories and spatial coordinates.

Stage 2: Detection results are formatted into prompts for Llama-3.2-Vision to generate structured English medical descriptions.
