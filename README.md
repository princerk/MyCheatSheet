# MyCheatSheet
A cheat sheet for general software installations and other frequently occurring problem

## Installing required cuda drivers and library to run deeplearning models on gpu
1. Install cuda driver using the script given here https://cloud.google.com/compute/docs/gpus/add-gpus
2. Download libcudnn run time and dev .dev files
3. sudo dpkg -i install <libcudnn run time library>
4. sudo dpkg -i install <libcudnn dev library>

## Setting virtual environment for python3

1. sudo apt-get install virtualenv -y
2. virtualenv -p python3 venv

## Installing python3-dev
sudo apt-get install python3-dev



