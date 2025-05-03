🧠 Uncovering the Hidden Treasures of the Mushroom Kingdom
A Deep Learning-Based Classification Analysis
📌 Overview
This project focuses on the visual classification of mushroom species using deep learning techniques. By leveraging transfer learning, our goal is to accurately categorize mushrooms into three genera — Boletus, Lactarius, and Russula — which are commonly found in diverse regions across the world. The ultimate objective is to develop a robust and reliable mushroom recognition system based on visual attributes that can assist in education, conservation, and field applications.

🛠️ Technologies Used
Python 3.10.x

TensorFlow / Keras

Flask (Backend)

HTML / CSS / JavaScript (Frontend)

OpenCV

NumPy & Pandas

🧠 Model Architecture
The mushroom classification model is built using transfer learning with a pre-trained convolutional neural network (CNN). This approach leverages the knowledge of a model trained on a large dataset (such as ImageNet) and fine-tunes it on our mushroom dataset to enhance classification performance. The trained model is saved as:
📂 Mushroom Classification Model.h5

📁 Project Structure
bash

AI-Mushroom-Classification-Analysis-master/
├── Dataset/                 # Labeled mushroom images (train/test)
│   ├── train/
│   └── test/
├── Flask/                   # Flask web application
│   ├── static/              # CSS, JS, images
│   ├── templates/           # HTML templates
│   ├── uploads/             # Uploaded user images
│   └── app.py               # Main Flask application
├── IBM Files/               # IBM Cloud deployment files
├── Training files/          # Training scripts & notebooks
├── images/                  # Project screenshots & images
├── Mushroom Classification Model.h5   # Trained model
├── Mushroom Classification Project Demonstration.mp4  # Demo video
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
📂 Dataset Overview
The dataset contains labeled images from three mushroom genera, each split into train and test directories:
🍄 Boletus
🍄 Lactarius
🍄 Russula

🖼️ Demo Screenshots
Home Page
Displays the project landing page where users can upload mushroom images.

Classification Result
Shows the predicted genus of the uploaded mushroom image along with confidence scores.

⚙️ Installation & Setup
📦 Using Conda (Recommended)
bash

# Create a new Conda environment
conda create -n mushroom_classifier python=3.10

# Activate the environment
conda activate mushroom_classifier

# Clone the repository
git clone https://github.com/Rohitmh09/AI-Mushroom-Classification-Analysis.git
cd AI-Mushroom-Classification-Analysis-master

# Install dependencies
pip install -r requirements.txt
🐍 Using Python venv
bash

# Create a virtual environment
python -m venv mushroom_env

# Activate the environment
# On Windows:
mushroom_env\Scripts\activate

# On macOS/Linux:
source mushroom_env/bin/activate

# Install dependencies
pip install -r requirements.txt
Note: If Flask and TensorFlow are not included in requirements.txt, install them manually:

bash

pip install flask tensorflow
🚀 Running the Application
bash

# Navigate to the Flask directory
cd Flask

# Start the Flask web application
python app.py
Now open your browser and go to 👉 http://localhost:5000 to access the application.

🔮 Future Enhancements
✅ Expand classification to include more mushroom species
✅ Develop a mobile application for real-time field identification
✅ Provide detailed biological information for each species
✅ Integrate geographical metadata to boost classification accuracy

✅ Conclusion
This project demonstrates the powerful application of deep learning and transfer learning in biological image classification. By building an accurate mushroom classification system, we contribute to the field of biodiversity recognition and promote a deeper understanding of mushroom species diversity worldwide. The system lays the foundation for educational tools, conservation efforts, and real-world field applications.