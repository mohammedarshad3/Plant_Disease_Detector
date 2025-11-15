Plant Disease Detection Using Deep Learning

A deep-learning based system that detects crop diseases from leaf images using a Convolutional Neural Network (CNN).
The project includes:

A trained model (.h5)

Prediction script

Remedies & disease descriptions

A Streamlit web app

Example images and screenshots



---

🚀 Features

✔ Classifies plant diseases from leaf images
✔ Shows the confidence score
✔ Displays description + remedies for the predicted disease
✔ Simple Streamlit web interface
✔ Lightweight, fast, and easy to run


---

📦 Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Download the trained model

Download the model from Drive:

👉 Model Link:
https://drive.google.com/file/d/190XKlIX47r497C2W54c1Env5c-WAH8zu/view?usp=sharing

Place the file in the root folder and rename it:

best_model.h5


---

▶️ Running the Web App

streamlit run app.py

This opens the web UI where you can upload a leaf image, and the model will display:

Predicted disease

Confidence

Description

Remedies



---

🧪 Example Output

Here’s a sample CLI run:

python predict.py sample_images/sample1.jpg

Output:

Predicted: Tomato___Late_blight (92.17%)


---

🖼 App Screenshots

🏠 Home Page

<img src="screenshots/Home.png" width="600">

📤 Upload Page

<img src="screenshots/Upload.png" width="600">

📊 Output Page

<img src="screenshots/Output.png" width="600">
---

📁 Project Structure

📂 Plant Disease Detector
│── app.py
│── predict.py
│── requirements.txt
│── class_indices.npy
│── remedies.json
│── README.md
│── sample_images/
│── screenshots/


---

🧠 Model Training Info

Framework: TensorFlow / Keras

Input size: 224 × 224

Trained on: PlantVillage dataset

Optimizer: Adam

Loss: Categorical Crossentropy



---

🙌 Acknowledgements

This project was created for academic purposes and is based on open datasets and deep learning frameworks.
