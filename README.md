# Create python 3.9 environment if using conda

conda create --name egg_detection python=3.9

# Activate the conda environment

conda activate egg_detection

# Install dependencies

pip install -r requirements.txt

# Check cuda version

nvcc --version

# Train the computer vision model

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124

# Trained model-runs are stored in the runs folder

C:\Users\user_name\runs\detect\train19
