# Underwater Fish Detection using Deep Learning

This project focuses on detecting underwater fish species from video or image datasets using deep learning models (e.g., YOLO, Faster R-CNN).  
It is part of my Master's Thesis work at Åbo Akademi University.

---

## 📁 Project Structure
Underwater Fish Detection/
│
├── .dvc/                ← DVC config & cache linking
├── Experiments/         ← Training runs, configs, model results
├── Notebooks/           ← Jupyter notebooks for EDA & testing
├── Reports/             ← Thesis figures, charts, PDFs, results
├── Scripts/             ← Python scripts (training, preprocessing)
├── Tests/               ← Unit / integration tests
│
├── .dvcignore
├── .gitattributes
├── .gitignore
├── Environment.yml      ← Conda environment (reproducibility)
├── LICENSE
├── README.md
├── Requirements.txt     ← (optional pip-based install)
└── template.py          ← Starter script or entry point



## Setup Instructions

1. Clone the repository
  
   git clone https://github.com/mdrafatanzir/underwater-fish-detection.git
   cd underwater-fish-detection
   
2. Create and activate the environment

   conda env create -f environment.yml
   conda activate underwater_fish_detection

3. Initialize DVC and pull data (if remote storage is set)

   dvc init
   dvc pull
4. Run Jupyter Notebook

   jupyter notebook
   
 ## Datasets

    Datasets used in this project:

	NTNU Underwater Fish Dataset (Zenodo)
	Deep Fish Object Detection (Kaggle)

## Tools & Libraries
	Python 3.11
	PyTorch & TorchVision – model training and evaluation
	OpenCV – image processing
	DVC – dataset and experiment versioning
	Jupyter Notebook – interactive experimentation
	Albumentations – data augmentation

## Reproducibility
This project uses Git for code version control and DVC for data versioning to ensure full reproducibility of experiments.

## Future Work
-Experiment with multiple detection models (YOLOv8, Faster R-CNN)
-Evaluate model performance across datasets
-Integrate real-time video inference
