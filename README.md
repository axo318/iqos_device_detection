<h1> IQOS Device Detection </h1>

1. **Data Directory**: Contains all pictures divided into three sections. All of them contain two folders (true, false) with IQOS and NO_IQOS images respectively
	1. all: Contains latest processed images for training and validation
	2. all_old: Contains the original pictures with non-consistent names
	3. test: Contains custom pictures for testing the model.
2. **Model Directory**: Contains the saved model weights for fast initialization
3. **model_building**: Jupyter notebook which builds, trains and saves the model.
4. **model_testing**: Jupyter notebook which initializes the trained model and predicts labels for the pictures in the "test" data folder

