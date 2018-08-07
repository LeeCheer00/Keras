Two persons recognition use keras, train model and deploy.
==========================================================
![upload](kerastest.png)


Run it!
-------
* File1: `python 1realtimev.py 0 `#opencv open the webcam and show it in the window, Para 0 is camera's id.\<br>
* File2: `python 2facezone.py 0 `#Recognize the face zone.\<br>
* File3: `python 3dataface.py 0 1000 /path/to/your/data/folder/ `# 0 1000 is the number of picture we cut from webcam, /path/to/you/data/folder/ is the directory we store our photoes.\<br>
* File4: `python load_face_dataset.py `#load the dataset to memoery.\<br>
* File5: `python 5facetrainusekears.py `#save the model to model directory.\<br>
* File6: `python evaluate.py `# Use the model we saved, and output the accuracy.\<br>
* File7: `python 7recognition.py  0 `# The final product.\<br>
