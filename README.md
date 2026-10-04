# Neural Network from Scratch
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-Matrix_Operations-brightgreen?logo=numpy&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version_Control-orange?logo=git&logoColor=white)

A customizable **neural network model** built from scratch in Python, developed for studying both the practical implementation of neural networks and the impact of different hyperparameters on model performance.

---

## 📁 Project Structure

The project is divided into three main files:

- **Rede.py** — Implements the `NeuralNetwork` class, which contains the FeedForward, Backpropagation, and Learn methods.

- **Gera_Dados.py** — Implements a dataset generator for training the neural network, storing samples in the format **Input | Output** in the file **Dados.txt**.

- **RN.py** — Allows the user to choose hyperparameters such as **number of layers**, **neurons per layer**, **learning rate**, and **training rounds per epoch**.

---

## 🛠️ Tools & Libraries
- **[Python](https://www.python.org/)** — Main programming language.
- **[Numpy](https://numpy.org/doc/)** — Library for efficient matrix computations.
- **[Git](https://git-scm.com/)** — Version control.

---

## 🚀 How to Run

With Python installed:

```bash
git clone https://github.com/Ivan-V246/Rede-Neural-Base.git
cd Rede-Neural-Base/
pip install -r requirements.txt
cd src/
python Gera_Dados.py
python RN.py
```

`RN.py` will instantiate the `NeuralNetwork` class with user-defined parameters and display the **expected outputs** alongside the **model outputs** for each input in the training set, as well as the total error margin for that version of the model.

> **Note:** By default, the network and data generator are configured to learn the logical expression **((A and B) or C)**. Therefore, the first layer must have **3 neurons** and the last layer must have **1 neuron** for correct operation. This is easily adjustable for training with other objectives and architectures.
