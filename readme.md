This project teach on how to automatically login in shopee.com and find your purchases and the total the amount that you spent. Once get all the data it's automatically open excel file and send it in gmail. It can also login in gmail using  personal account and send the excel file.





python3 -m venv venv

source venv/bin/activate



pip install requirements.txt


#!/bin/bash

echo "Installing Google Chrome..."
wget -q https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt --fix-broken install -y
rm google-chrome-stable_current_amd64.deb

echo "Installing dependencies..."
pip install -r requirements.txt

echo "Setup complete!"

