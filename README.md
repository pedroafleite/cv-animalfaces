# Computer Vision

We have a spin on a classical problem of computer vision, in which we have to classify **cat** and **dog** images using Keras.

[See the jupyter notebook here](https://github.com/pedroafleite/cv_animalfaces/blob/main/keras_with_animal_faces.ipynb).

In this [Kaggle dataset](https://www.kaggle.com/andrewmvd/animal-faces), we also have a third class, named **wild**, that encompasses wild animals such as lions, leopards, tigers, foxes, wolves, and so on (other carnivorans overall). Therefore, instead of being a binary classification problem (dogs or cats), we have a multiclass classification problem (dogs, cats or wild).

Using a convnet with dropout and data augmentation, we obtained a **0.9675** accuracy score.

Using a pre-trained convnet (imagenet) with data augmentation, we obtained a **0.9850** accuracy score.

We also trained the dataset with other known classification algorithms ([see the jupyter notebook here](https://github.com/pedroafleite/cv_animalfaces/blob/main/predict-multiple-animal-faces-use-different-ml.ipynb)) such as logistic regression, SVM (Support Vector Machine), random forest and decision tree -- but to lesser results.
