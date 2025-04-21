# How to set up Virtual environment
1. Check Python version with python3 --version
2. Create venv
python3 -m venv ports_venv
3. Activate venv
source ports_venv/bin/activate

# How to install all packages in requirements.txt
pip install -r /path/to/requirements.txt

# How to push an existing repository from the command line
git remote add origin git@github.com:racc0909/techacademy_ports.git
git branch -M main
git push -u origin main