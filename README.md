# Keras-Image-Classifier
Keras is a high level wrapper built on top of Tensorflow which provides excellent support to create deep learning models with just a few lines of code.

## Getting Started
This is a simple image classifier implemented using Keras using very few lines of Python code. We will be using a machine with Keras, SciPy, PIL installed. We will be using Kaggle Dogs vs. Cats dataset which can be downloaded from (https://www.kaggle.com/c/dogs-vs-cats)

### Installing
First, if you do not have Tensorflow installed do that by using the following command:
```
pip install tensorflow
```
Then, install Keras:
```
pip install keras
```
Also, you will need Pillow which is a Python Imaging library:
```
pip install pillow
```
#### Setup
Create a directory named **data** containing folders **train** and **test**. Each of these folders will contain folders for the two classes: **dogs** and **cats**. It should look like this:
```
data/
    train/
        dogs/
            dog001.jpg
            dog002.jpg
            ...
        cats/
            cat001.jpg
            cat002.jpg
            ...
    validation/
        dogs/
            dog001.jpg
            dog002.jpg
            ...
        cats/
            cat001.jpg
            cat002.jpg
            ...
 ```
We will be using 1000 images for each of the classes. Additionally we will use 400 images for validation, to evaluate our model.
 
#### Execute
Navigate to the directory where you have your **data** folder and run *classify.py*
```
python classify.py
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Reference Code: (https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html)
* Inspiration: Siraj Raval (https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A)
