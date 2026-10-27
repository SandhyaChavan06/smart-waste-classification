# smart-waste-classification
♻️ Smart Waste Classification System
A beginner-friendly AI/ML project that classifies waste images into six categories using deep learning and transfer learning with MobileNetV2.
📌 Project Overview
The Smart Waste Classification System takes an image of a waste item and predicts its category. The project is built in Google Colab using Python and TensorFlow, with a Gradio interface for image-based predictions.
🎯 Objectives
- Classify waste images into common categories.
- Train an image classification model using transfer learning.
- Evaluate model performance with accuracy, loss graphs, a classification report, and a confusion matrix.
- Provide a simple web interface for users to upload an image and view predictions.
- Support awareness of waste sorting and recycling.
🗂️ Categories
The model predicts one of these six categories:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash
🛠️ Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Gradio
- GitHub
- Hugging Face Spaces (optional deployment)
📊 Project Workflow
1. Download and inspect the waste image dataset.
2. Prepare image paths and labels.
3. Split the dataset into training, validation, and test sets.
4. Resize and preprocess images.
5. Train a MobileNetV2-based image classifier.
6. Plot training and validation accuracy and loss.
7. Evaluate the model on a separate test set.
8. Test predictions using new images.
9. Build a Gradio web application.
10. Upload the project to GitHub and optionally deploy it online.
📁 Repository Structure
smart-waste-classification/
├── app.py
├── requirements.txt
├── class_names.json
├── waste_classification_model.keras
└── README.md
The trained model file and class_names.json are required to run the web app.
🚀 Run the Web App Locally
1. Clone this repository
git clone https://github.com/YOUR-USERNAME/smart-waste-classification.git
cd smart-waste-classification
Replace YOUR-USERNAME with your GitHub username.
2. Install dependencies
pip install -r requirements.txt
3. Start the app
python app.py
Open the local Gradio URL shown in the terminal, then upload a waste image to get a prediction.
🧪 Model Evaluation
The notebook evaluates the model using:
- Test accuracy and test loss
- Precision, recall, and F1-score
- Confusion matrix
- Training and validation accuracy graph
- Training and validation loss graph
Add your actual test accuracy and screenshots of the graphs here after you run the notebook. Do not enter estimated results.
📚 Dataset
This project is designed for the TrashNet household-waste image dataset.

Dataset repository: https://github.com/garythung/trashnet

Check the dataset's license and usage terms before redistribution. This project uses image categories such as cardboard, glass, metal, paper, plastic, and trash.
🌐 Deployment
The Gradio application can optionally be deployed on Hugging Face Spaces:
1. Create a new Space at https://huggingface.co/spaces
2. Choose Gradio as the SDK.
3. Upload app.py, requirements.txt, class_names.json, and waste_classification_model.keras.
4. Wait for the build to finish and test the live app.
⚠️ Limitations
- Dataset images may have relatively controlled backgrounds.
- Predictions on real-world photos may be less accurate than predictions on dataset-like images.
- The model's score is not a guarantee that its prediction is correct.
- The predicted category does not determine local recycling rules. Check local waste-management guidance, especially for hazardous or contaminated items.
🔮 Future Improvements
- Add more diverse, real-world waste images.
- Improve performance on underrepresented classes.
- Compare MobileNetV2 with other models.
- Add multilingual disposal suggestions.
- Explore camera-based waste detection and smart-bin integration.
👩‍💻 Author
Your Name
AI/ML Student

Update this section with your name, college, and portfolio links if desired.
📄 Disclaimer
This project is an educational demonstration of image classification. It should not be used as the sole basis for recycling, safety, or hazardous-waste decisions.
