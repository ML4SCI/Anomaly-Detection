# Anomaly Detection Using Contrastive Learning (Electron-Photon)

![Anomaly Detection](https://user-images.githubusercontent.com/113689877/193227014-c6edf7e3-1618-4d93-a089-171128fec6aa.png)

## Overview
This project aims to detect anomalies, specifically electrons, by training a model solely on photon data using contrastive learning techniques. By leveraging contrastive learning, the model learns to distinguish between normal photon data and anomalous electron data, thus enabling accurate anomaly detection.

## Dataset
### Top Quark Dataset:
- **Description:** Top quark dataset for reference.
- **Download Link:** [Top Quark Dataset](https://drive.google.com/drive/folders/1WXc1-wetvaiufNzAcVg23DEBK2QBYhp9?usp=sharing)

### Electron-Photon Dataset:
- **Description:** Dataset containing both electron and photon data for training and evaluation.
- **Download Link (Part 1):** [Electron-Photon Dataset Part 1](https://cernbox.cern.ch/index.php/s/sHjzCNFTFxutYCj/download)
- **Download Link (Part 2):** [Electron-Photon Dataset Part 2](https://cernbox.cern.ch/index.php/s/69nGEZjOy3xGxBq/download)

## Requirements
- Strong knowledge of Python programming language.
- Familiarity with machine learning frameworks such as TensorFlow or PyTorch.
- Basic understanding of contrastive learning principles.

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/anomaly-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd anomaly-detection
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare the dataset:
   - Download the dataset files from the provided links.
   - Organize the dataset files into appropriate directories (e.g., `data/train`, `data/validation`).

2. Train the anomaly detection model:
    ```bash
    python train.py --dataset <path_to_dataset> --epochs <num_epochs> --batch_size <batch_size>
    ```

3. Evaluate the trained model:
    ```bash
    python evaluate.py --dataset <path_to_dataset> --model <path_to_trained_model>
    ```

## Documentation
For detailed documentation on the project, including API references and usage examples, please refer to the [Documentation](docs/) directory.

## Contributing
We welcome contributions from the community to improve this project. If you'd like to contribute, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md).

## License
This project is licensed under the [MIT License](LICENSE).
