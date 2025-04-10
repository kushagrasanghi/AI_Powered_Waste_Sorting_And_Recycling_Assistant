# AI_Powered_Waste_Sorting_And_Recycling_Assistant

Install python 3.12.3
inside cmd
pyhton --version

Install miniconda
miniconda Test
-conda 

After that
inside conda cmd 
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
This installs CUDA and CuDnn 

Create Conda environment(Go to drive where you have enough space avoid placing in main OS drive (ex C: drive))
Navigate to Project folder create new folder named envs inside that
conda create --name waste_sorting python=3.9 -y

Activate the environment
conda activate waste_sorting

Tensorflow installaton
python -m pip install "tensorflow<2.11"

To check if GPU is used or not(inside same conda cmd)
python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"

install packages/libraries
pip install numpy==1.23.5
pip install matplotlib
pip install keras-efficientnet

other packages(required)
pip install keras opencv-python pandas scikit-learn tqdm pillow


inside conda cmd 
conda list (It should list all the installed packages)
