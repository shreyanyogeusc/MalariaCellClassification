
# Malaria Cell Classification

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Gradio](https://img.shields.io/badge/Gradio-3.x-green.svg)

## Overview

This project uses Convolutional Neural Networks (CNNs) to classify malaria-infected and uninfected cells based on microscopic images. The goal is to demonstrate how deep learning can assist in medical diagnostics.

### Features
- Image classification using CNN.
- Interactive web interface using Gradio for real-time predictions.
- High accuracy achieved using a dataset of cell images.

---

## Dataset

- **Source**: [NIH Malaria Dataset](https://ceb.nlm.nih.gov/repositories/malaria-datasets/)
- **Details**:
  - Total Images: `1200`
  - Image Dimensions: 128x128 pixels
  - Two Classes: `Parasitized (Infected)` and `Uninfected`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/MalariaCellClassification.git
   cd MalariaCellClassification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook.

---

## Usage

### Running the Jupyter Notebook
1. Open `MalariaCellClassification.ipynb` in Jupyter Notebook.
2. Execute the cells to preprocess data, train the model, and evaluate performance.

### Running the Gradio Interface
1. Run the Gradio code in the notebook.
2. Access the web interface via the provided link.
3. Upload a cell image to get predictions.

---

## Results

- **Accuracy**: `<Add accuracy value>`
- **Precision**: `<Add precision value>`
- **Recall**: `<Add recall value>`

Sample predictions using the Gradio app:
- Parasitized: Confidence 89%
- Uninfected: Confidence 11%

---

## File Structure

```
MalariaCellClassification/
│
├── dataset/                # images dataset
├── MalariaCellClassification.ipynb  # Main notebook
├── mdl_wts.keras           # Trained model weights
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
├── LICENSE                 # License for the project
└── .gitignore              # Ignore unnecessary files
```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

Feel free to reach out for any queries or feedback:
- **Email**: `yoge@usc.edu`
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/shreyan-yoge)
