# Image-Caption-Generator--

🖼️ Image Caption Generator using Deep Learning (CNN–RNN)

An end-to-end Image Caption Generation system built using Deep Learning, combining CNN-based feature extraction and RNN-based sequence modeling, with an interactive Gradio web interface for real-time caption generation.

📌 Project Overview

This project automatically generates natural language captions for input images.
It uses a pretrained CNN (VGG16) to extract visual features from images and an LSTM-based RNN to generate meaningful captions word by word.

The system is designed as:
A research/academic project
A GitHub portfolio project
A deployable demo using Gradio

🚀 Key Features
🧠 Deep Learning–based caption generation
🖼️ Image feature extraction using VGG16
🔁 Sequence modeling with LSTM
🧾 Tokenization & padding for text processing
🌐 Interactive Gradio UI
📦 Modular and reusable code
✅ Easy to run and extend

🏗️ Architecture
Input Image
     ↓
CNN (VGG16)
     ↓
Image Feature Vector
     ↓
Embedding Layer
     ↓
LSTM Decoder
     ↓
Generated Caption

🛠️ Tech Stack
Python 3
TensorFlow / Keras
NumPy
Pickle
Gradio
VGG16 (Pretrained CNN)

📂 Project Structure
├── image_caption_generatorAIML.ipynb   # Model logic & caption generation
├── gradio.ipynb                        # Gradio web interface
├── tokenizer.pkl                       # Saved tokenizer
├── model.h5                            # Trained captioning model
├── README.md                           # Project documentation
└── requirements.txt                    # Dependencies

📊 Dataset Used
Flickr8k Dataset
~8,000 images

Each image has 5 human-annotated captions
Widely used for image captioning research
Note: Due to size constraints, the dataset is not included in this repository.

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Required Files

Ensure the following files are present:
model.h5
tokenizer.pkl
(These are generated after training or provided separately.)

▶️ Running the Project
🔹 Run Caption Generator Notebook

Open and execute:
image_caption_generatorAIML.ipynb
🔹 Launch Gradio Web App

Run:
gradio.ipynb


You will get a browser-based UI where you can upload an image and receive a caption instantly.

🧪 Sample Output
Input Image	Generated Caption
🏞️ Image --	"a dog is running through the grass"

🧠 Model Details
CNN: VGG16 (ImageNet pretrained, top layers removed)
RNN: LSTM
Embedding Dimension: 256
Optimizer: Adam
Loss Function: Categorical Crossentropy

🎯 Use Cases
Assistive technology for visually impaired users
Automated image tagging
Social media content generation
AI-based content understanding
Academic research and learning

📌 Limitations
Limited vocabulary (dataset dependent)
Performance constrained by dataset size
Works best on common objects/scenes
🔮 Future Enhancements
🔄 Replace VGG16 with ResNet / EfficientNet
🧠 Add Attention Mechanism
🌍 Multilingual caption generation
☁️ Cloud deployment (Hugging Face / AWS)
📱 Mobile-friendly interface

👨‍💻 Author
Vansh Garg
Computer Science Student | AIML & Data Science Enthusiast

Snehil Kanaujia 
Computer Science Student | AIML & Data Science Enthusiast

⭐ Acknowledgements
Flickr8k Dataset creators
TensorFlow & Keras documentation
Gradio team

📜 License
This project is intended for educational and research purposes.
