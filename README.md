# 🖼️ Image Caption Generator using Deep Learning (CNN + LSTM)

An end-to-end **Image Caption Generation** system built using **Deep Learning**, combining **CNN-based feature extraction** and **LSTM-based sequence modeling**, with an interactive **Gradio web interface** for real-time caption generation.

---

## 📌 Project Overview

This project automatically generates **natural language captions** for images.  
It uses a **pretrained VGG16 CNN** to extract visual features and an **LSTM-based language model** to generate meaningful captions word by word.

The project is designed to be:
- 📊 Academically strong (AIML / Deep Learning concepts)
- 💼 Resume & GitHub worthy
- 🌐 Easily deployable using **Gradio**

---

## 🚀 Key Features

- CNN + RNN based Image Captioning
- Pretrained **VGG16** for image feature extraction
- **LSTM** for sequence prediction
- Tokenization & padding for text processing
- Interactive **Gradio UI**
- Clean and modular inference pipeline
- Easy to extend with new datasets or models

---

## 🧠 Model Architecture

Input Image
↓
VGG16 (CNN)
↓
Image Feature Vector
↓
Embedding Layer
↓
LSTM Network
↓
Dense + Softmax
↓
Generated Caption

yaml
Copy code

---

## 🗂️ Project Structure

├── image_caption_generatorAIML.ipynb # Model logic & caption generation
├── gradio.ipynb # Gradio web interface
├── tokenizer.pkl # Saved tokenizer
├── model.h5 # Trained captioning model
├── README.md # Project documentation

yaml
Copy code

---

## 📚 Dataset

- **Flickr8k Dataset**
- Each image has **5 human-written captions**
- Used for training and evaluating the captioning model

> Dataset is not included due to size constraints.

---

## ⚙️ Technologies Used

- **Python 3**
- **TensorFlow / Keras**
- **NumPy**
- **Gradio**
- **VGG16 (Transfer Learning)**
- **LSTM (Sequence Modeling)**

---

## 🧪 How It Works

1. Upload an image
2. Image is preprocessed and passed to **VGG16**
3. Extracted features are fed into the trained model
4. Caption is generated one word at a time
5. Final caption is displayed via Gradio UI

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/vanshgargg12/image-caption-generator.git
cd image-caption-generator
2️⃣ Install Dependencies
bash
Copy code
pip install tensorflow numpy pillow gradio
3️⃣ Run Gradio Interface
Open and run:

bash
Copy code
gradio.ipynb
OR run directly from notebook cells.

🖥️ Sample Output
pgsql
Copy code
Input Image: A dog running on the beach
Generated Caption: "a dog is running through the sand"
📌 Use Cases
Assistive technology for visually impaired users

Image search and indexing

Social media automation

Content moderation and tagging

AI-powered photo description tools

📈 Future Improvements
Use ResNet/Inception instead of VGG16

Add BLEU score evaluation

Train on Flickr30k / MS-COCO

Deploy on Hugging Face Spaces

Add multilingual caption support

👨‍💻 Author
Vansh Garg
Computer Science | DATA SCIENCE
UPES Dehradun

Snehil Kanaujia
Computer Science | AIML
UPES Dehradun


⭐ Acknowledgements
Flickr8k Dataset

TensorFlow & Keras Documentation

Gradio Team

📜 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute it.

⭐ If you like this project, don’t forget to star the repository!
