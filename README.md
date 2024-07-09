Customized_AI_Kitchen
Intel Project
Overview
Customized_AI_Kitchen is a Flask-based web application that helps users identify ingredients in uploaded images and adjust recipe quantities based on the number of servings. The application uses a pre-trained TensorFlow model for image classification and processes recipes from a CSV dataset.

Download Our Custom Dataset
Custom Database

Dataset Overview
Our custom dataset consists of images categorized into 36 distinct classes. These classes represent various ingredients commonly used in cooking. The class names include:

Asafoetida
Brown rice
Butter
Cabbage
Capsicum
Cardamom powder
Carom seeds
Carrot
Coriander leaves
Curry leaves
Dry red chili
Eggplant
Fenugreek leaves
Fenugreek seeds
Garlic
Ginger
Green chili
Jaggery
Lemon
Mango
Milk
Mustard seeds
Onion
Raw mango
Red chili powder
Ridge gourd skin
Rosemary
Saffron strands
Sugar
Sunflower oil
Tamarind
Tea leaves
Tomato
Turmeric powder
White lentils
Yellow corn meal flour
The dataset is organized into three main directories:

Train: Contains images used for training the model.
Test: Contains images used for testing the model's performance.
Validation: Contains images used for validating the model during training to prevent overfitting.
This well-structured dataset ensures comprehensive coverage of each class, enabling robust training and accurate classification by the model.

Table of Contents
Installation
Setup
Running the Application
File Structure
Installation
Clone the Repository
git clone https://github.com/HarshwardhanJain/Customized_AI_Kitchen.git
cd Customized_AI_Kitchen
Uninstall Dependencies
To prevent conflicts between libraries, uninstall the following packages:
pip uninstall -y Flask
pip uninstall -y pandas
pip uninstall -y numpy
pip uninstall -y tensorflow
pip uninstall -y Werkzeug
pip uninstall -y matplotlib
pip uninstall -y Flask-WTF
Install Dependencies
pip install -r requirements.txt
Setup
Download the Dataset and Model
1. Custom_Recipe_Dataset.csv:

Ensure you have Custom_Recipe_Dataset.csv.
Place it in the directory Customized_AI_Kitchen/.
2. Custom_Image_Classification_Trained_Model.h5:

Ensure you have Custom_Image_Classification_Trained_Model.h5.
Place it in the directory Customized_AI_Kitchen/.
Running the Application
Run the Flask Application
python AIKitchen.py
Access the application at http://127.0.0.1:5000/.
File Structure
Customized_AI_Kitchen/
│
├── static/
│   ├── backgrounds/
│   │   ├── background1.jpg
│   │   ├── background2.jpg
│   │   ├── background3.jpg
│   │   ├── background4.jpg
│   │   └── background5.jpg
│   ├── uploaded_images/
│   └── styles.css
│
├── templates/
│   ├── action.html
│   ├── base.html
│   ├── display_images.html
│   ├── home.html
│   ├── index.html
│   ├── missing.html
│   └── recipe.html
│   └── upload.html
│
├── .gitattributes
├── .gitignore
├── AIKitchen.py
├── Custom_Image_Classification_Trained_Model.h5
├── Custom_Recipe_Dataset.csv
├── README.md
└── requirements.txt
Note
Ensure that the library versions are accurately installed and that the processes are carefully followed. If there are any errors, please refer to the tutorial video.
Ensure all file paths are correct.# CUSTOMIZED-AI-KITCHEN
