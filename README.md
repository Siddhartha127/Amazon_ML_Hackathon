# Amazon_ML_Hackathon

# Entity Value Extraction from Product Images
## Overview
This project, created for the Amazon ML Hackathon, extracts entity values (e.g., weight, dimensions) from product images using a combination of YOLOv8 for object detection and PyTesseract for OCR.

## Key Components
1. YOLOv8 : Detects relevant product areas in images.
2. PyTesseract : Extracts text from detected regions.
3. OpenCV & Pillow : Preprocess images to enhance OCR accuracy.
4. Batch Processing : Efficiently processes large datasets.

## Workflow
1. Object Detection : YOLOv8 identifies bounding boxes of interest.
2. OCR: PyTesseract extracts and cleans text from detected areas.
3. Post-processing : Extracted text is formatted into "value unit" (e.g., "2 grams").

## Fine-tuning
The YOLOv8 model was fine-tuned on a custom dataset using semi-supervised learning to improve detection accuracy and entity extraction.

## Considerations
- Accuracy : Combining object detection and OCR improves extraction reliability.
- Efficiency : Batch processing enables scalability for large datasets.
- Flexibility : Easily adaptable to different product types.

## Potential Enhancements
- Further YOLOv8 fine-tuning.
- Improved post-processing for complex cases.
- Exploration of advanced OCR solutions.
