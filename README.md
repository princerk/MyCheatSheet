# MyCheatSheet
A cheat sheet for general software installations and other frequently occurring problem

## Minimal vim configuration
https://github.com/princerk/vim-config/blob/master/vimrc

## Installing required cuda drivers and library to run deeplearning models on gpu
1. Install cuda driver using the script given here https://cloud.google.com/compute/docs/gpus/add-gpus
2. Download libcudnn run time and dev .deb files
3. sudo dpkg -i install &lt;libcudnn run time library>
4. sudo dpkg -i install &lt;libcudnn dev library>

## Setting virtual environment for python3

1. sudo apt-get install python3-dev
2. sudo apt-get install virtualenv -y
3. virtualenv -p python3 venv

## Give a user read write permission
https://askubuntu.com/questions/487527/give-specific-user-permission-to-write-to-a-folder-using-w-notation

## Run jupyter-notebook on cloud machine
1. Open a port 8888 on machine
2. install jupyter and do the modify config
```cmd
$ jupyter-notebook --generate-config
```

Open jupyter config file and add following lines at the end

```cmd
c = get_config()
c.NotebookApp.ip = '0.0.0.0'
c.NotebookApp.port = 8888
c.NotebookApp.open_browser = False
```

## Transfer learning using keras
https://stackoverflow.com/questions/41378461/how-to-use-models-from-keras-applications-for-transfer-learnig

## Supervisor commands
http://www.onurguzel.com/supervisord-restarting-and-reloading/

## Generate ssh keys
check if you have already ssh key generated.
```cmd
cat ~/.ssh/id_ras.pub
```
Generate if not present already.

```cmd
cd ~
ssh-keygen -t rsa
```
access public key at ~/.ssh/id_rsa.pub

```cmd
cat ~/.ssh/id_rsa.pub
```

