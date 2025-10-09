![Screenshot 2025-06-16 210618](https://github.com/user-attachments/assets/98004a94-eede-4e01-8969-b499e6f88050)
![Screenshot 2025-06-16 210411](https://github.com/user-attachments/assets/57d4c854-e172-4068-801b-8821656f969a)
![Screenshot 2025-06-18 021208](https://github.com/user-attachments/assets/0a3b4c70-a434-4544-b2d7-6db3e63cbc2c)
![Screenshot 2025-06-18 020946](https://github.com/user-attachments/assets/64957fe8-b724-4d6e-9a15-d5d38811cad4)
![Screenshot 2025-06-18 021237](https://github.com/user-attachments/assets/049713af-0843-46d9-982a-c7075c885100)

# 🖼️ AI Image-to-Story Generator

Turn images into vivid stories, poems, or captions using cutting-edge AI models!  
This application combines vision and language models to let users upload an image, generate a caption using **BLIP**, and transform it into creative text using **TinyLLaMA**.

---

## ✨ Features

- **📸 Image Captioning**: Uses [BLIP](https://huggingface.co/Salesforce/blip-image-captioning-base) to describe uploaded images.
- **🧠 Text Generation**: Uses [TinyLLaMA](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0) to generate:
    - 🎭 Short stories
    - 📝 Poems
    - 💬 Social media-style captions
- **🎨 Tone Customization**: Choose from 5 tone styles: `funny`, `emotional`, `dark`, `creative`, and `formal`.
- **⚡ Runs on GPU**: Optimized for local machines with 6GB+ VRAM (e.g., RTX 4050).

---

## 🛠️ Tech Stack

| Component      | Model / Tool                          |
|----------------|----------------------------------------|
| Image Captioning | `Salesforce/blip-image-captioning-base` |
| Text Generation  | `TinyLlama/TinyLlama-1.1B-Chat-v1.0`     |
| Interface        | `Gradio`                              |
| Environment      | `Python`, `Torch`, `Transformers`     |

---

## 🚀 How It Works

1. **Upload an Image**
2. **BLIP** generates a caption describing the image
3. Select the desired **Tone** and **Type** (`story`, `poem`, `caption`)
4. **TinyLLaMA** creates the output using your custom prompt
5. Output is displayed with clear formatting

---

## 💻 Setup Instructions

---

1. **Clone this repo**

git clone https://github.com/yourusername/image-to-story-generator.git
cd image-to-story-generator


2. **Create virtual environment**

python -m venv venv
source venv/bin/activate    # or venv\Scripts\activate on Windows


3. **Install requirements**

pip install -r requirements.txt


4. **Run the app**

python app.py


---

## 🎨 Examples
| Image         | Caption                                        | Story/Poem Example                              |
| ------------- | ---------------------------------------------- | ----------------------------------------------- |
| 🌸 Pink Lotus | *“a pink lotus flower with a blue background”* | *“As the sun shimmers through morning dew\...”* |

---
## 📂 Project Structure

.
├── app.py                 # Gradio UI

├── blip_caption.py        # BLIP captioning logic

├── story_generator.py     # TinyLLaMA story/poem/caption generator

├── requirements.txt

└── README.md

---

## 🧠 Inspiration
This project was built to explore multimodal generative AI — combining computer vision and language models to create meaningful, artistic content from images.

---

## 📃 License
MIT License
Feel free to fork, modify, and contribute!

---

---

## Issues

Feel free to add any issues you find 

---

## 🙋‍♂️ Author
Deshan Senanayake
📧   smddsenyake@gmail.com

🔗   LinkedIn : https://www.linkedin.com/in/deshan-senanayake-7a0695292/

🔗   GitHub : https://github.com/Deshan-Senanayake

