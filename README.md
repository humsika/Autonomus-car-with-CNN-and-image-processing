### Self-Driving Car using CNN and Image Processing

Project Autopilot predicts the steering angle for a self-driving car using deep learning. Inspired by NVIDIA's End-to-End Learning for Self-Driving Cars, this project utilizes Convolutional Neural Networks (CNNs) to analyze road conditions and determine the appropriate steering angle.

🔹 Features

Predicts steering angles using deep learning.

Utilizes CNNs for image-based road analysis.

Trained on Udacity’s Behavioral Cloning dataset.

Implemented in Python using Keras.

📂 Dataset

Download the dataset from here and extract it into the repository folder.

Data Format: filename.jpg angle,year-mm-dd hr:min:sec:millisec

🚀 How to Run

Preprocess Data: Run LoadData_V2.py to generate labels and features pickle files.

Train Model: Execute Train_pilot.py to train the model.

Test on Video: Run AutopilotApp_V2.py to see the model in action.

🛠 Installation

Install dependencies using:

pip install -r requirements.txt

For Conda users:

conda install --file requirements.txt

📌 Note

For collaboration or project inquiries, reach out via LinkedIn.

🔗 References

Inspired by Akshay Bahadur and NVIDIA’s research on self-driving technology.

