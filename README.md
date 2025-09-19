How to deploy in local
sudo apt update

sudo apt upgrade -y

sudo apt install -y python3

python3 --version

sudo apt install -y python3-pip

sudo apt install -y python3-venv

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python app.py

To remove the virtual env - deactivate
