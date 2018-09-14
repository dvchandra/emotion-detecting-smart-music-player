This is a machine learning project which basically plays music according to facial expression of user.The project has been taken from this website:"http://www.paulvangent.com/2016/06/30/making-an-emotion-aware-music-player/"and is the property of DR. Paul van gent.
This is an attempt to learn and mimic his work and research.
Pre-requisites:
1.python 2.7
2.Opencv 2.4.9
3.virtual env or anaconda (optional)
4.source images (for training)

Working:
1.run the preprocess.py file to store images in sorted_Set file
2.run extract.py to extract the required part of sorted image(face) into dataset folder
3.run train.py to train the model and check its accuracy
ps: accuracy improves with time
4.now run 1.py using command promt:
          a.open cmd and call update.py program
          b.now use command: update 1.py
          c.this will allow user to provide new inputs which would directly store in the dataset folder
5.now run 2.py and it will access a excel file with the help of which music would be played.
6.finally run 3.py which will play music according to facial expression of the user.