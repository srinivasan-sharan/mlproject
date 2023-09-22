## end to end ml project

This is an end to end ml project that follows the modular coding approch to convert your jupyter notebook models, into usable web applications.

In this project, we are using the student marks dataset to see how the students background and marks can be used to predict their scores in other subjects.

------
To run this project, download and unzip the file. 

using the anaconda prompt, cd into the working directory and then follow the instructions:

create a virtual env using anaconda:
`conda create -p venv python==3.8 -y`

activate the virtual env using:
`conda activate venv/`

after activating the virtual environment, uncomment the `-e` in requirements.txt and then install the dependencies using :
`pip install -r requirements.txt`

then to run the file use:
`python app.py` 

the app route:  `http://127.0.0.1:5000/predictdata`
