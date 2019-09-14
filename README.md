Aim
To develop a model using machine learning algorithms which will predict the genre of a song by
itself.

Goals
1. To develop a machine learning code and test it on a dataset.
2. To classify the songs in two genres.

Abstract
Music tagging or music tagger is a software which can classify songs into their respective genre.
This project included many subparts which are further mentioned in this document.
In this mini-project, we have used logistic regression(binary classification) but the same or more
better results can be achieved by SVM(Support Vector Machine) and Neural Networks.
This kinds of software are mainly used in apps like saavn,spotify,gaana,etc where music of
same genre are classified together.


This project includes-
1. Dataset extraction
      a. A music genre is a conventional category that identifies pieces of music as
          belonging to a shared tradition or set of conventions. It is to be distinguished from
          musical form and musical style. The features extracted from these waves can
          help the machine distinguish between them.
      b. The features in this dataset are extracted from the GTZAN genre collection
          provided at the site of Marsyas (Music Analysis, Retrieval and Synthesis for
          Audio Signals). It is an open source software framework for audio processing
          with specific emphasis on Music Information Retrieval applications.
      c. It consists of 1000 audio tracks each 30 seconds long. It contains 10 genres,
          each represented by 100 tracks. The tracks are all 22050 Hz Mono 16-bit audio
          files in .wav format.
      d. Features are extracted using libROSA library. LibROSA is a python package for
          music and audio analysis. It provides the building blocks necessary to create
          music information retrieval systems. The extracted features were saved in a csv
          file.
2. Logistic regression:-
    a. Logistic regression is used used to classify data into groups(binary classification
        i.e two groups) .
    b. Logistic function is a sigmoid function which gives values in between 0 and 1.
    c. Logistic regression includes further many subparts:-
        i. Hypothesis representation- Hypothesis is a function which we will feed
           into machine and the machine will process the parameters using that
           function. Hypothesis for logistic regress is a sigmoidal function.
       ii. Cost function- Cost function is basically the difference between the
            machine predicted value and the actual value.
       iii. Decision boundary- This concept includes rounding off of the predicted
            result to either 1 or 0. For eg, if the programmer sets the decision
            boundary to 0.6, then all the predicted values below 0.6 will be rounded
            off to 0 and those above 0.6 will be rounded off to 1. By changing the
            value of decision boundary programmer can increase the efficiency of the
            program.

    d. The above image represents the sigmoid function and its equation.
    e. Logistic regression can also be used to classify data into more than two classes
       but it’s discussion is beyond the scope of this documentation.

3. Gradient descent
    a. Gradient descent is a first-order iterative optimization algorithm for finding
       the minimum of a function.
    b. To find a local minimum of a function using gradient descent, one takes
       steps proportional to the negative of the gradient (or approximate gradient)
       of the function at the current point.


Future aspects:
This project can also be accomplished by using neural networks,SVM and Logistic
regression(one vs all). All of the above mentioned techniques can be used to classify audio
files into more than two genres.
References:
1. http://marsyas.info/downloads/datasets.html
2. http://librosa.github.io/librosa/
3. https://www.kaggle.com/insiyeah/musicfeatures
