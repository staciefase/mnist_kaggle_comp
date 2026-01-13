# mnist-digital-recognition-kaggle

This is my first attempt at building a dense neural network using a subset of the MNIST digital dataset. Kaggle dataset link is here: https://www.kaggle.com/datasets/wasiqaliyasir/digital-mnist-dataset

More info about the challenge is here: https://www.kaggle.com/c/digit-recognizer

I have the basic version of Posit Cloud which is how I'm running Rstudio right now. I probably need to update my subscription to more than just the basic plan, and/or optimize my code somehow, bc I keep running into session memory limits. I'll figure it out later.

Broadly, what I did was this:
- Grabbed a subset of the train.csv and test.csv dataset (first 50 rows)
- Formatted the data to be used by keras (flattened and split)
- Normalized it (divided pixel vals by 255 to give me vals between 0 and 1)
- Created a dense neural network with 128, 64, and 10 neurons to each layer, respectively
- Ran it against my training data and generated validation and accuracy metrics

What I still need to do:
- Run it against test data (which is in a different format than the training data)
- Validate that the model works against test data
- Check the accuracy and confusion matrix
- Optimize
- Submit the sample submission to the kaggle platform for eval

Probs I keep running into
- Memory issues mostly
- I'm doing this in R, not Python, so it's slow going...sigh
- This is my first time doing a neural network and I've been told that a CNN is a better approach than the way I'm doing that. So probably something to explore next.
- I don't really know what I'm doing so it's a lot of trial and error. Which I suppose is the point. Still.

 
