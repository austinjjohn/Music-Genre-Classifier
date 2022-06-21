# Music Genre Classifier   
This project implements a Conventional Neural Network Model that is trained on the GTZAN Dataset to identify and classify genres of popular songs.
The GTZAN Dataset consists of 10 genres (folders), each consisting of 100, 30 second long audio files (.wav)
* Blues
* Classical 
* Country
* Disco
* Hip Hop
* Jazz
* Metal
* Pop
* Reggae
* Rock

The **Data** folder consists of the following files/**folders**
* **genres_original** - Collection of the audio files
* **images_original** - A visual representation of each audio file.
* features_30_sec.csv - A csv file containing all the features from the audio files.
* features_3_sec.csv - A csv file containing features from the same audio files, but the files have been split to 3 second long files. Hence increasing the size of our dataset.

## Program
To run the model, use the ipynb file in the repo. Install the necessary packages with `pip install -r requirements.txt`. The ipynb file uses `python3`.