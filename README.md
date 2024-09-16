# Create python 3.9 environment if using conda

conda create --name egg_detection python=3.9

# Activate the conda environment

conda activate egg_detection

# Install dependencies

pip install -r requirements.txt

# Install Cuda and CuDNN if your system has Nvidia GPU, to use gpu for training

Download and install both from Nvidia website

# Check cuda version

nvcc --version

# Train the computer vision model

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
