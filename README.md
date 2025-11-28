# MLP MNIST Classifier

Simple PyTorch Multi-Layer Perceptron (MLP) model trained on the MNIST dataset.  
This project includes preprocessing, model architecture, training loop, and accuracy reporting.

---

## 🛠 Features
- Fully-connected neural network (MLP) with 3 hidden layers
- Training loop with loss and accuracy reporting
- Save best model weights automatically
- CPU/GPU compatible

---

## 📂 Project Structure

```
mlp-mnist-classifier/
 ├── mlp_mnist.py         # Main Python file with model and training code
 ├── README.md            # This file
 ├── requirements.txt     # Python dependencies
 ├── models/              # Folder where trained models are saved
 └── data/                # MNIST dataset (downloaded automatically)
```

---

## ⚡ How to Run

1. Create a virtual environment:

```bash
python -m venv venv
# Activate environment:
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run training:

```bash
python mlp_mnist.py
```

> The model will automatically download MNIST dataset and save the best weights in `models/best_model.pt`.

---

## 📈 Results

- Tracks training and validation accuracy
- Saves best model for inference

---

## 🧰 Requirements

- Python 3.8+  
- torch  
- torchvision  
- numpy  

---

## 📚 References

- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)  
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

---

## 📄 License

MIT License
