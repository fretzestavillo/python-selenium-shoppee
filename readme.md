This project automates the process of logging into Shopee, retrieving purchase history, calculating the total amount spent, and exporting the data to an Excel file. Additionally, the script logs into Gmail using a personal account and sends the Excel file via email.


Getting Started

To set up the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/fretzestavillo/python-selenium-shoppee.git

```

2. Change Directory:

```bash
cd python-selenium-shoppee/

```


3. Set Up Virtual Environment:

```bash

python3 -m venv venv
source venv/bin/activate

```

4. Install Dependencies:

```bash

pip install requirements.txt


```
5. Install Google Chrome:

```bash


wget -q https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt --fix-broken install -y
rm google-chrome-stable_current_amd64.deb

```

6. Run the Script:


```bash


python main.py

```