# Zebrafish Neuroblastoma Measurement Project

**Author:** Kevin Alejandro Gonzalez Villanueva

## Overview
Object detection is one of the most critical tasks in computer vision. This repository addresses the detection of neuroblastoma—a prevalent malignant pediatric tumor—by applying computer vision techniques to analyze an *in vivo* zebrafish model.

To tackle this detection problem, we utilize image processing methods such as morphological operations, thresholding, and segmentation. These techniques will ultimately provide the structured data necessary to build an environment for training a neural network via supervised learning.

## Repository Structure
The entire workflow is detailed and implemented within the Jupyter Notebook provided. 

```text
├── Imágenes exportadas/       # Generated output images (saved automatically)
├── dataset/                   # Main folder for the raw TIFF images (Needs to be downloaded)
├── main_analysis.ipynb        # Core notebook with morphological operations and segmentation
└── README.md                  # Project documentation
```

## Requirements
To run this project, you will need Python 3.8+ and the following libraries:
* numpy
* matplotlib
* tifffile
* opencv-python (or scikit-image, depending on your implementation)
* jupyter (to run the `.ipynb` file)

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/YourRepositoryName.git
   cd YourRepositoryName
   ```

2. **Download the Dataset:**
   The raw dataset is not included in this repository due to size constraints. Please download the dataset `.zip` file from [Insert Link Here] and extract it.
   
3. **Set up the Directory:**
   Ensure the extracted dataset folder is set as the main root directory for the analysis, matching the `base_path` variables in the notebook.

4. **Run the Notebook:**
   Open the `.ipynb` file in PyCharm, Jupyter Notebook, or JupyterLab, and run the cells sequentially. The segmented output images will be saved automatically in the `Imágenes exportadas/` folder.

## Data and Code Availability
The dataset and the original `proyecto_e1.ipynb` file can be downloaded as a `.zip` archive from: **[Insert Link/DOI Here]**.

## License
[MIT License or Creative Commons]
