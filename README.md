# Logistic-regression-machine-learning-model
Constructing a logistic regression model to classify breast cancer cells

## Project overview
My goal here was to construct a logistic regression model from the ground up that could classify breast cancer cells to a high degree of accuracy.

## Development progress
I began by constructing simple 2 parameter, 4 instance set of data to build my model around and was debugging throughout. I started working through manually without functions and loops then once i got it working i put within functions and for i loops including cost function then plotted for a few different 4 sample datasets. 

Then added b variables and bugfixes.

From there i upscaled to 3 dimension and adjusted code as needed. Then applied to the breast cancer data set which cause overflow issues. So i introduced clipping into the model to avoid dividing by 0 and overflow. 


## Results
When applied to real-world cancer dataset with added b variable I achieved 91.6% accuracy on the training-set. Important to note The accuracy is measured on all of its training data so doesn't take into account any extrapolating classifications.


