# ListOpenWindows -- Python Open Windows Lister

A Microsoft Windows 10 python script for listing all open windows by &lt;PID>: &lt;Window title>


## Install 

### Windows 10

```terminal
git clone https://github.com/Donny-GUI/ListOpenWindows.git
cd ListOpenWindows
# windows msi installed all users + PATH
python list_open_windows.py
# windows store install
py list_open_windows.py

```

### WSL2

```WSL
git clone https://github.com/Donny-GUI/ListOpenWindows.git
cd ListOpenWindows
python3 list_open_windows.py
```

### from fresh WSL2 Install
```shell
sudo apt update && sudo apt upgrade
sudo apt install python3 python3-pip python-is-python3
sudo apt-get update
cd
git clone https://github.com/Donny-GUI/ListOpenWindows.git
sudo cp /ListOpenWindows /mnt/c/
cd
cd /mnt/c/ListOpenWindows && python list_open_windows 

```
### Creating command for list open windows for wsl2 --  [lsw]
with wsl 
``` 
sudo " \nalias lsw='cd ~/mnt/c/ListOpenWindows && python3 list_open_windows.py && cd' \n" >> ~/.bashrc && cd ~ && source .bashrc
```

```nano
