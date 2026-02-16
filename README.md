# LLM Project
### THIS WEBSITE IS IN PROGRESS, IT WILL be done in like a few months
## Overview
This is a comprehensive documentation about the LLM project, detailing its architecture, features, installation, and usage.

## Architecture
The architecture of the LLM project is designed to be modular, enabling easy scalability and maintenance. The system comprises the following key components:
- **Model Components**: Description of the core models used.
- **Data Processing**: Overview of data handling and preprocessing.
- **Inference Pipeline**: Explanation of how predictions are made.

## Features
- High-performance language model for text generation.
- Support for multiple input formats.
- Easy integration with various applications.
- Customizable training capabilities.

## Quick Start Guide
To get started with the LLM project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Ramacsv/super-duper-bassoon.git
   ```
2. Create the conda environment and install dependencies (conda-only):
   ```bash
   conda env create -f environment.yml
   ```
3. Activate the environment:
   ```bash
   conda activate llm-training
   ```
4. Run the application:
   ```bash
   python main.py
   ```

## CUDA / GPU
This repository provides a conda-only environment that targets CUDA 12.1 (pytorch-cuda=12.1). The environment.yml includes the pytorch and nvidia channels. Make sure your system has the appropriate NVIDIA drivers installed for CUDA 12.1 before using GPU features.

If you prefer CPU-only usage, remove `pytorch-cuda=12.1` and install the CPU builds of PyTorch through the same environment.yml channels or use a separate environment.

## Training (example)
If you want to run a quick local training run:
```bash
mkdir -p data
echo "Training text..." > data/sample.txt
python train.py
```

## Next Steps
- Explore the examples provided in the `examples` directory.
- Review the model training documentation for custom model implementation.
- Contribute to the project by raising issues or submitting pull requests.
