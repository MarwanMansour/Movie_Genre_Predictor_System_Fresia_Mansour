# Can I watch it?

Can I watch it is a project aimed at filling missing values for movie genres using other available data, like

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the needed packages.

```bash
pip install numpy pandas matplotlib gensim sklearn nltk keras tensorflow

```
# Usage
The code for this project is all collected in a jupyter notebook since the data is all used from one file.

1- Download the zip file [Project_Movie_Genre_Predictor.zip](https://drive.google.com/drive/folders/1E1i3iQ3uKkBkG0B_hk8cV4BoHGeUehnb?usp=sharing), open the jupyter notebook Genre Prediction.ipynb.

2-From the Cell menu in the top taskbar, press 'Run All' to train all the models.

3- To make a prediction on a custom movie summary, after running all cells, go to the bottom of the notebook, and input a summary for your movie.
!['picture'](https://raw.githubusercontent.com/MarwanMansour/Movie_Genre_Predictor_System_Fresia_Mansour/master/Capture.PNG?token=AI54SAGYNJTXLQ3OT46RF4C45SULM)

# Data Used
The data used in this project is downloaded from [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset#movies_metadata.csv)

!['picture'](https://raw.githubusercontent.com/MarwanMansour/Movie_Genre_Predictor_System_Fresia_Mansour/master/Capture1.PNG?token=AI54SAHSO6FK4R7KCM3RX4S45SVZK)
From the movies_metadata.csv file, we are using the fields: genres, overview and tagline.

!['picture'](https://raw.githubusercontent.com/MarwanMansour/Movie_Genre_Predictor_System_Fresia_Mansour/master/Word%20Cloud%20Movie.png?token=AI54SAFIMW6WKNVHD23DCMK45SV7E)

Attached above is a word cloud of the words mentioned the most in movies summaries.

!['picture'](https://raw.githubusercontent.com/MarwanMansour/Movie_Genre_Predictor_System_Fresia_Mansour/master/index.png?token=AI54SAH5J5BXKTQ6QXJYNYC45SWF2)

Attached above is the distribution of genres for all the movies, showing a clear data imbalance.

# Best Performance
!['picture'](https://raw.githubusercontent.com/MarwanMansour/Movie_Genre_Predictor_System_Fresia_Mansour/master/index1.png?token=AI54SACZMFR3JVDULQCMRG245SWOU)

Attached above is the model loss for the LSTM Recurrent neural network implemented for our project. Which approaches an asymptote at around 10 epochs.
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
