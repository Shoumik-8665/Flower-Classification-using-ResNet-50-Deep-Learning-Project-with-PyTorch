# Flower-Classification-using-ResNet-50-Deep-Learning-Project-with-PyTorch
This project uses a pre-trained ResNet-50 model and fine-tunes its final layer to classify 102 flower categories from the Oxford Flowers-102 dataset. It's a practical example of transfer learning in computer vision using PyTorch.
 Dataset
Oxford 102 Flower Dataset

Contains 8189 images of flowers categorized into 102 different species.

Divided into training, validation, and test splits.

🧠 Model Architecture
ResNet-50 pre-trained on ImageNet

Final fully connected layer replaced with:

python
Copy
Edit
model.fc = nn.Linear(model.fc.in_features, 102)
Trained for 5 epochs with Adam optimizer

🛠 Technologies Used
Python

PyTorch

torchvision

Matplotlib

tqdm

Jupyter Notebook

🧪 Results
✅ Training and validation loss tracked for each epoch

🎯 Final test accuracy reported

📊 Visualizations of predictions with true labels

🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/resnet50-flower-classification.git
cd resnet50-flower-classification
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook

bash
Copy
Edit
jupyter notebook ResNet-50\ Flowers\ Training.ipynb

📄 License
This project is licensed under the MIT License.
