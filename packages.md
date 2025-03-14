# Virtual Environment
sudo apt update
sudo apt install python3-venv
python3 -m venv myenv # To create a virtual environment
source myenv/bin/activate # To activate this virtual environment

# install jupyter notebook
pip install jupyter

# open jupyter notebook
jupyter notebook

# Install numpy
pip install numpy

# Install pandas
pip install pandas
pip install openpyxl // to read .xlsx and export DataFrame into .xlsx file

# install matplotlib
pip install matplotlib

# install seaborn
pip install seaborn

# upgrade all python libraryes
pip install --upgradelibrary-name

# delete Virtual environment(ubuntu)
deactivate
rm -rf myenv
