# Deep-Learning-Skin-Disease
This project uses the YOLO (You Only Look Once) object detection algorithm to classify different types of skin diseases from images. It demonstrates how deep learning can assist in medical image analysis, potentially aiding dermatologists in diagnosis.

📁 Project Structure
SKIN_DISEASE_CLASSIFICATION_USING_YOLO.ipynb – Main Jupyter notebook containing the complete workflow including:

Data loading and preprocessing

Model configuration and training

Evaluation and testing

Visualization of detection results

🛠️ Technologies Used
Python

YOLOv5/YOLOv8 (via Ultralytics or custom implementation)

OpenCV

NumPy, Pandas

Matplotlib, Seaborn

PyTorch / TensorFlow (depending on the implementation)

Jupyter Notebook

📊 Dataset
The dataset consists of labeled images of various skin conditions. Each image is annotated for object detection training using YOLO format (bounding boxes + class labels).

Note: Ensure the dataset is downloaded and structured properly before running the notebook.

🚀 Getting Started
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/skin-disease-yolo.git
cd skin-disease-yolo
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Download the Dataset

Place the dataset in the data/ folder with subfolders for training, validation, and testing images and labels.

Run the Notebook

Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook SKIN_DISEASE_CLASSIFICATION_USING_YOLO.ipynb
📈 Results
The trained YOLO model can detect and classify skin diseases with bounding boxes and confidence scores.

Example outputs are shown in the notebook.
