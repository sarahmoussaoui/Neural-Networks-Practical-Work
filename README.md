# Neural Networks: Practical Work

Practical work (TPs) for the Neural Networks module, completed as a group of three. Each lab is in its own folder and builds on the concepts seen in class, from the first neuron models to deeper networks.

## Repository structure

```
.
├── TP1/     # Practical work 1
├── TP1.2/   # Practical work 1, part 2
├── TP2/     # Practical work 2
├── TP3/     # Practical work 3
├── TP4/     # Practical work 4
├── TP4.1/   # Practical work 4, part 2
├── TP5/     # Practical work 5
├── TP6/     # Practical work 6
└── README.md
```

## Getting started

```bash
git clone https://github.com/sarahmoussaoui/Neural-Networks-Practical-Work.git
cd Neural-Networks-Practical-Work

python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install numpy pandas matplotlib scikit-learn tensorflow notebook
```

These packages cover the usual needs of a neural networks lab (numerical computing, data handling, plots, classical machine learning, deep learning, and Jupyter). 

## Usage

Each TP folder is self-contained. Open the folder, then run its notebooks or scripts:

```bash
jupyter notebook              # for .ipynb files
python your_script.py         # for .py files
```

Run the notebooks from top to bottom so every cell has the variables it needs.
