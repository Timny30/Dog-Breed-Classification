# 🐶 Image Classification Pipeline

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Bash Scripting](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

> **Automating contestant validation and breed identification for a citywide dog show registration system.**

By processing submitted pet images, this application determines whether a pet is actually a dog and correctly classifies its breed. It benchmarks three different Convolutional Neural Network (CNN) architectures—**ResNet, AlexNet, and VGG**—to evaluate the trade-off between model classification accuracy and computational runtime.



## 🛠️ Technologies & Tools
* **Language:** Python 3
* **Deep Learning Framework:** PyTorch / Torchvision
* **Image Processing:** PIL (Pillow)
* **Dataset References:** ImageNet
* **Automation:** Bash (`.sh`) for batch execution




## 🚀 Features
* **Command-Line Interface (CLI):** Flexible parameter passing via `argparse` to configure directories, model architectures, and reference files.
* **Automated Label Extraction:** Formats and generates ground-truth labels directly from raw image filenames.
* **Pre-trained CNN Inferences:** Performs image classification across three distinct network architectures.
* **Dog vs. Non-Dog Verification:** Cross-references classification results against a comprehensive dictionary of dog breeds (`dognames.txt`).
* **Statistical Performance Analysis:** Calculates percentage accuracies for dog detection, non-dog detection, and breed matching.
* **Batch Execution & Benchmarking:** Automated bash scripts to run, profile, and compare all models in a single command.




## ⚙️ Running the Project
You can run all three models sequentially and output the results directly to the terminal or text files using the automated bash script:
```bash
sh run_models_batch_uploaded.sh
