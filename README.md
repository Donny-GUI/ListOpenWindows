# ListOpenWindows -- Python Open Windows Lister :snake: :receipt:

A Microsoft Windows 10 python script for listing all open windows by &lt;PID>: &lt;Window title>


##  :open_file_folder:   Install 

###  :desktop_computer: Windows 10 :desktop_computer:

```terminal
git clone https://github.com/Donny-GUI/ListOpenWindows.git
cd ListOpenWindows
# windows msi installed all users + PATH
python list_open_windows.py
# windows store install
py list_open_windows.py

```

### :heavy_dollar_sign:  WSL2  :heavy_dollar_sign:

```WSL
git clone https://github.com/Donny-GUI/ListOpenWindows.git
cd ListOpenWindows
python3 list_open_windows.py
```

###  :heavy_dollar_sign: :sparkles: from fresh WSL2 Install :sparkles: :heavy_dollar_sign:
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
