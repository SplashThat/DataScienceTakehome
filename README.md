Howto activate Jupyter Notebook:


sh> sudo pip install virtualenv

sh> sudo pip install virtualenvwrapper


sh> cd ~/Workspace/splashthat

sh> git clone git@github.com:SplashThat/DataScienceTests.git

sh> cd DataScienceTests


sh> virtualenv venv

sh> cd venv

sh> source bin/activate

(venv) sh> pip install jupyter


(venv) sh> cd ../interviews2017

(venv) sh> jupyter notebook


Opens browser on http://localhost:8888


(Once you're done:)

(venv) sh> deactivate
