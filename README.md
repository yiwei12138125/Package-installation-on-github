# Package-installation-on-github
Package installation 
cd in your file( you should create a file in your disk if you like)
git clone + link（for example https://github.com/owencqueen/PolymerGNN.git)  
if you get an error about SSL in the previous step
Try typing git config --global http.sslVerify false
cd in this clone file
Check if there is a file which name is setup.py
pip install -e. or pip install .
conda list to check whether the installation is successful
