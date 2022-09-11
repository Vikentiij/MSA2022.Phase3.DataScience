Required Software:
Python 3.9+
Text Editor for Python (Visual Studio Code with Python extension installed is recommended)
Recommended:

Anaconda
Virtualenv
Setting Up:
Install the libraries listed in the requirements.txt via the command:

pip install -r requirements.txt
Recommended to use a virtual environment either from either virtualenv or anaconda. This setup helps isolate project dependencies from user dependencies as to avoid version conflicts.

Tensorboard:
Tensorboard is an added feature to the skeleton project. Run

tensorboard --logdir output/logs/
to run tensorboard. The main points of interests are accuracy and loss graphs. The tensorboard application can then be opened via the site http://localhost:6006/.