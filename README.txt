
$$ ATTENTION: TO USE ALL THE JUPYTIER NOTEBOOK YOU NEED TO MEET TO THE REQUIRMENTS FILE
                (The requirements file is not really accurate because there is in it libraries that are not used in the notebooks
                and this because we forgot to use a specific python environment for this project, so we used our main python environment)


#------------------------------------------------------
BRIEF DESCRIPTION OF THE JUPYTER NOTEBOOKS

There is 3 ipynb files
    - 2 of them were used for building the classifiers (EMOTION and GENDER)
    - And the last one is our main program that implement the two classifiers that build


#------------------------------------------------------
EXPLICATION ON HOW TO USE THE 2 JUPYER NOTEBOOKS USED FOR BUILDING THE CLASSIFIERS

Both classifier have the same structure, they are divided in 8 sections:
    1) Librairies Importation: it's mandatory to import the libraris in order to correctly use the rest of the cells
    2) Data Importation & Data-Pre-processing: To import the data, visualize it  and pre-process it
    3) Model Architecture: To select the model structure that you want to use
    4) Compile Model: To compile the selected model
    5) Model training: To train the model, plot the loss, metrcis, etc.
    6) Model evaluation: To train the model with all the training data (validation + train), evaluate on the test set, print confusion matrix, etc.
    7) Save the model: To save the model selected
    8) Load the model: To load a specific model that was already saved

For the 2nd, 3rd, 5th, 6th, 7th and 8th part, the first cell is a cell where you can fix the hyperparamters.
This first cells are the only one where modification are allowed for a guarented running. Each hyperparamter is described and have explicit names.
Some additional comments are also there in order to give more explications on how to use the hyperparamters or the next cells.

$$ IMPORTANT:   You have to download the data linked to each classifier in order to import the data.
                You could find the links to download the data in the subfolder data.

#------------------------------------------------------
EXPLICATION ON HOW TO USE THE JUPYER NOTEBOOKS USED FOR THE IMPLEMENTATION OF OUR MAIN PROGRAM

This classifer is divided in 3 sections:
    1) Librairies Importation: it's mandatory to import the libraris in order to correctly use the rest of the cells
    2) Global Variables: it's the only cell where modifications are allowed
                            it's mandatory to specify in this cell appropriate path for a GENDER CLASSIFIERS model and EMOTION CLASSIFIERS
                            it's also mandatory to set the boolean IS_WEBCAM_INPUT to true if you want to use your webcam as video input
                                if it's set to false, it's mandatory to provide a video path that will be taken as input by the algorithm
    3) Main Program: The cell that allows you to start the program and to use the 2 classifiers in real time (webcam) or on a video

If you want to exit the program, you just have to press the key 'esc' on your keyboard

$$ IMPORTANT:   You have to download the model linked to each classifier in order to import the model.
                You could find the links to download the model in the subfolder data.

                You also could find in the data folder a video that could be used as input for testing purpose.
                (If you want to see the result, you could find the same video in which was applied our pipline in the presentation folder)