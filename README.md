# Living-Object-Classification-Model

###IMPORTANT###

---Please ensure changing the Runtime Type under Runtime to GPU from CPU(otherwise the process can take much time than needed and it's unnecessary)---


Dataset used ---> https://www.kaggle.com/datasets/salader/dogs-vs-cats




kaggle.json can be found from kaggle profile then API

line[13] is not important but rather you want to find the accuracy thus you can use it.

About the Cat you can save a file name by cat.jpg and omit the path in line[17]


//Seems like I searched for converting the array to strings so i tried out some alternative:

  if predictions_cnn[0][0] > 0.5:
        print("Prediction: Dog")
    else:
        print("Prediction: Cat")


