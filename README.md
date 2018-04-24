# Speech Recognition

In this project I'll show you my own code designed to recognize voice commands that can be used in smart home. The code is written in Python and and uses various packages such as numpy or librosa. Plotly package is used only to present the results in most transparent way. Machine learning is done using SVC function from scikit-learn package. I tried others functions from this package, but SVC gave the most satisfying results. This code isn't prerfect and more work needs to be done. It's planned to improve extracting of the features from audio signals and also to use TensorFlow and DTW algorithm. 

Before you head to the notebook make sure you've got all necessary packages installed. If you're missing some of them use these commands:

```javascript
pip install librosa
pip install plotly 
pip install scikit-learn
```
or
```javascript
sudo pip install librosa
sudo pip install plotly
sudo pip install scikit-learn
```
To install scikit-learn you need to have Python newer than 3.3, nupmy newer than 1.8.2 and SciPy newer than 0.13.3.

Audio files are in Recordings folder. In each of them person says 13 different words that can be used to control smart home. There is around 1s pause between every words. All the files are names by this rule:

IIIIII_AA_G_TT_N.wav

where:

I - student's index number

A - age of the student

G - gender (K- female, M- male)

TT - time when it was recorded (using 24h system)

N - number of the recording

There are also files named 1, 2, 3, etc. The purpose of naming them this way is to load many files easier way.

### Unfortunately graphs from Plotly package dont'w show up on github, so i recommend using this link http://nbviewer.jupyter.org/github/KacperTurek/Speech-Recognition/blob/master/Speech%20Recognition.ipynb to view the notebook with all the graphs.

Every feedback is welcome. Enjoy.
### Kacper Turek
