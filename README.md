# Directed and Heterogeneous Graph Neural Networks for Academic Recommendation

Welcome to the repository for my Honours Dissertation at Heriot-Watt University! This project focuses on leveraging **directed graph neural networks (DGNNs)** and **heterogeneous graph neural networks (HGNNs)** to enhance academic citation recommendations. By modeling citation relationships as directed and heterogeneous graphs, this project aims to integrate novel approaches for improving recommendation accuracy in academic networks.

## 📑 Project Overview

### Objective
- Enhance the accuracy of academic recommendations by integrating **directed graph neural networks** with **heterogeneous graph neural networks**.
- Capture single-directional citation relationships that are often overlooked in standard heterogeneous graph models.

### Key Contributions
1. **Directed-Heterogeneous Integration**: Combines directed graph neural networks (to model citation flows) and heterogeneous graph attention networks (to account for different node types).
2. **Novel Layer-wise Framework**: Proposes a novel layer-wise heterogeneous network to optimize for citation links not present in standard models.
3. **Improved Recommendation Accuracy**: Demonstrates the effectiveness of integrating directionality into heterogeneous structures through experimental analysis.

## 📚 D1 Report
For a detailed understanding of the project, you can refer to the [D1 Report](hwu_cs_dissertation_1_report.pdf) included in this repository. The report outlines:
- Problem Statement
- Research Objectives
- Preliminary Results
- Future Work

## 🚀 Features
- Models citation relationships using directed graph structures.
- Handles heterogeneous graph nodes (authors, papers) with attention mechanisms.
- Integrates directed graph convolutions to capture flow-based relationships.
- Benchmarks recommendation performance using standard academic datasets.

## 🛠️ Usage
### Prerequisites
1. Python 3.8+
2. PyTorch 1.10+
3. Additional dependencies in `requirements.txt`.

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-link
   cd your-repo-link
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model:
   ```bash
   python train.py --config configs/directed_heterogeneous.yaml
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py --model checkpoints/best_model.pth
   ```

## 📊 Results
- Preliminary experiments show a significant improvement in recommendation accuracy compared to baseline models.
- Full experimental results will be included in future updates.

## 🧑‍🏫 Mentor
This project is supervised by [Professor Wei Pang](https://researchportal.hw.ac.uk/en/persons/wei-pang) at Heriot-Watt University.

## 🌐 Repository Structure
```
.
├── D1Report.pdf        # Detailed project proposal and progress report
├── LICENSE             # Creative Commons (CC BY 4.0) License
└── README.md           # Project documentation

```

## 📚 License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
For commercial purposes, please contact [your_email@example.com] to obtain explicit permission.

## 📫 Contact
For any inquiries or collaboration opportunities, feel free to reach out to me at [yj2012@hw.ac.uk](mailto:yj2012@hw.ac.uk).

---

This project is part of my academic research and is under active development. Feedback and contributions are welcome!
