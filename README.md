# Computer Vision

We have a spin on a classical problem of computer vision, in which we have to classify **cat** and **dog** images. In this [Kaggle dataset](https://www.kaggle.com/andrewmvd/animal-faces), we also have a third class, named **wild**, that encompasses wild animals such as lions, leopards, tigers, foxes, wolves, and so on (other carnivorans overall). Therefore, instead of being a binary classification problem (dogs or cats), we have a multiclass classification problem (dogs, cats or wild).

Using a convnet with dropout and data augmentation, we obtained a **0.9675** accuracy score.

Using a pre-trained convnet (imagenet) with data augmentation, we obtained a **0.9850** accuracy score.
