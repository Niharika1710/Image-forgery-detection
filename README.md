# 🧠 Comprehensive Detection of Image Manipulations using Deep Learning

This repository presents a deep learning-based system to **detect and classify image manipulations**, including:

- **Splicing**
- **Copy-Move**
- **Deepfake**
- **Image Retouching**

We use a **hybrid architecture** involving CNNs, VGG16, GANs, and Vision Transformers (ViT) for robust and accurate detection.

---


---

## 📊 Datasets Used

- **CASIA v1.0 & v2.0** – Splicing
- **CoMoFoD** – Copy-Move
- **DFDC / DFD** – Deepfake
- **Realistic Tampering Dataset** – Retouching

---

## 🧠 Models Used

| Task          | Architecture             |
|---------------|---------------------------|
| Splicing      | CNN + VGG16               |
| Copy-Move     | GAN (patch-level)         |
| Deepfake      | Vision Transformer (ViT)  |
| Retouching    | Fine-tuned VGG16          |

---

## 🛠️ Setup

```bash
git clone https://github.com/yourusername/image-manipulation-detection.git
cd image-manipulation-detection
python -m venv venv
source venv/bin/activate  # (Windows: venv\Scripts\activate)
pip install -r requirements.txt
```
python app/detect.py --image path_to_image.jpg

| Manipulation Type | Accuracy |
| ----------------- | -------- |
| Splicing          | 87.5%    |
| Copy-Move         | 85.2%    |
| Deepfake          | 91.4%    |

Acknowledgments
-CASIA, CoMoFoD, DFDC, DFD for datasets

-PyTorch, TensorFlow, Hugging Face

-OpenAI tools for research assistance


