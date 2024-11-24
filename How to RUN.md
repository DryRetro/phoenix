
## Installation and Launch (Option 1)
1 - Updating system
```bash
sudo apt update
sudo apt install build-essential
```

2 - Run this command to install libs and enter activation code
```bash
make new
```

3 - Run to prepare wallets.json file with random User Agents and set up proxy to specific profile
```bash
make init
```

4 - Run System
```bash
make run
```


## Installation and Launch (Option 2)
1 Check is your python is 3.10
```bash
python3 --version
```
2 Install Libs

```bash
pip3 install -r requirements.txt
```

3 Check is chrome installed

```bash
google-chrome --version
```

4 Fill all data
Enter your wallet data to wallets.json and dont forget to use proxy.txt (each proxy from new line)


5 Make randomization
```bash
python3 useragents.py
```
