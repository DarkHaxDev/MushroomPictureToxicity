# MushroomPictureToxicity
Repository of an application for converting pictures of mushrooms to a toxicity classification.

MushroomPictureToxicity is an application that will (eventually) allow users to take pictures of mushrooms on their phones and have a machine learning model determine if the mushroom in the picture is toxic or not.

The project will be tackled in two cours:

1. Train a model  using Scikit-Learn on [this dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification) in order to classify if a given mushroom is toxic or not.
2. Train a model using Keras and TensorFlow on a [dataset](https://www.kaggle.com/datasets/lizhecheng/mushroom-classification) of mushroom images, with the outputs being features that the above model will use to classify toxicity.

My reasoning for the above:

* Although it might be simpler (and better) to use a neural network to look at images and just classify if it's toxic or not, I wanted to this give this method a try for experimentation's sake.
* I also wanted to test how difficult it is to have another machine learning algorithm create the features for another model to use.

I will attempt to make this project an end-to-end one:
* Package my models up in a format that's usuable for a phone (cloud or on-board)
* Use all the fancy DevOps tools and such.
* Etc.

Overall, this will be an interesting project whose results and code I hope will be of use to *somebody* out there. Enjoy my progress!
