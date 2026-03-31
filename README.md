# Document-Classifier
A Computer Vision project for automatic invoice company identification using logo classification.
The system detects and classifies invoices based on the company logo present in invoice images.

This project demonstrates how machine learning can automate document processing workflows such as accounting, invoice routing, and vendor identification.

#WORKFLOW
Invoice Image
      ↓
Image Preprocessing
      ↓
Logo Feature Extraction
      ↓
Trained Classification Model
      ↓
Predicted Company / Vendor

#STRUCTURE
invoice-logo-classification/
│
├── dataset/                # Training and testing images
├── models/                 # Saved trained models
├── train.py                # Model training script
├── predict.py              # Inference script
├── utils.py                # Helper functions
├── requirements.txt        # Dependencies
└── README.md

🧩 Technologies Used
-> Python
-> OpenCV
-> NumPy
-> Scikit-learn / Deep Learning model
-> Image Classification
-> Computer Vision

📈 Use Cases
-> Automated accounting systems
-> Invoice sorting pipelines
-> Vendor recognition
-> Document management automation
-> Enterprise RPA workflows

🧪 Future Improvements
-> Logo detection + classification (YOLO integration)
-> OCR + invoice data extraction
-> API deployment (FastAPI / Flask)
-> Real-time invoice processing
-> Multi-page PDF support
