# stock-2
How to Predict Stock Prices in Python using TensorFlow 2 and Keras

https://www.thepythoncode.com/article/stock-price-prediction-in-python-using-tensorflow-2-and-keras?fbclid=IwAR37T7f_fn2csftqOt3T3qc5dN4GQavyYa06CHruTsY_3fIbg9HlY9nPCM0


https://www.thepythoncode.com/article/stock-price-prediction-in-python-using-tensorflow-2-and-keras?fbclid=IwAR37T7f_fn2csftqOt3T3qc5dN4GQavyYa06CHruTsY_3fIbg9HlY9nPCM0

####################################### install  ########################################
pip3 install https://github.com/lhelontra/tensorflow-on-arm/releases/download/v2.1.0/tensorflow-2.1.0-cp37-none-linux_armv7l.whl
sudo apt install python3-dev python3-pip
sudo apt install python3-matplotlib python3-tk


# get a fresh start
sudo apt-get update
sudo apt-get upgrade
# remove old versions, if not placed in a virtual environment (let pip search for them)
sudo pip uninstall tensorflow
sudo pip3 uninstall tensorflow
# install the dependencies (if not already onboard)
sudo apt-get install gfortran
sudo apt-get install libhdf5-dev libc-ares-dev libeigen3-dev
sudo apt-get install libatlas-base-dev libopenblas-dev libblas-dev
sudo apt-get install openmpi-bin libopenmpi-dev
sudo apt-get install liblapack-dev cython
sudo pip3 install keras_applications==1.0.8 --no-deps
sudo pip3 install keras_preprocessing==1.1.0 --no-deps
sudo pip3 install -U --user six wheel mock
sudo -H pip3 install pybind11
sudo -H pip3 install h5py==2.10.0
# upgrade setuptools 40.8.0 -> 52.0.0
sudo -H pip3 install --upgrade setuptools
# install gdown to download from Google drive
sudo -H pip install gdown
# download the wheel
gdown https://drive.google.com/uc?id=11mujzVaFqa7R1_lB7q0kVPW22Ol51MPg
# install TensorFlow
sudo -H pip3 install tensorflow-2.2.0-cp37-cp37m-linux_armv7l.whl wrapt --upgrade --ignore-installed
# and complete the installation by rebooting
sudo reboot

sudo pip3 install sklearn
sudo pip3 install yahoo-fin

####################################### run  ########################################

cd Desktop/stock_1/
sudo python3 test.py


