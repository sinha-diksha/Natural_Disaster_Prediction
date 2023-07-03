# Natural Disaster Prediction Model

Welcome to the Natural Disaster Prediction Model repository! This project focuses on predicting different types of natural disasters, including floods, earthquakes, droughts, tsunamis, and hurricanes. Each prediction category has a dedicated directory containing datasets and an IPython Notebook (`.ipynb`) file with the corresponding prediction model.

## Project Structure

The repository is organized as follows:

- `floodPrediction/`: Directory for flood prediction
    - `datasets/`: Directory containing flood-related datasets
    - `flood_prediction.ipynb`: IPython Notebook with the flood prediction model

- `earthquakePrediction/`: Directory for earthquake prediction
    - `datasets/`: Directory containing earthquake-related datasets
    - `earthquake_prediction.ipynb`: IPython Notebook with the earthquake prediction model

- `droughtPrediction/`: Directory for drought prediction
    - `datasets/`: please access the dataset from this link (256mb is the size of the dataset)   https://www.kaggle.com/code/cdminix/starter-us-drought-meteorological-data/input
    - `drought_prediction.ipynb`: IPython Notebook with the drought prediction model

- `tsunamiPrediction/`: Directory for tsunami prediction
    - `datasets/`: Directory containing tsunami-related datasets
    - `tsunami_prediction.ipynb`: IPython Notebook with the tsunami prediction model

- `hurricanePrediction/`: Directory for hurricane prediction
    - `datasets/`: Directory containing hurricane-related datasets
    - `hurricane_prediction.ipynb`: IPython Notebook with the hurricane prediction model

## Environment Setup

To set up the environment and run the prediction models, please follow the steps below:
1. You should have a preferred code editor like VS Code, Google Collab, Jupyter Notebook, Anaconda (or your preferred code editor) to run these ipynb files.

2. Clone this repository to your local machine using the following command:

git clone [repository_url]

3. Alternatively, you can manually download the IPython Notebook files and datasets from each prediction category's directory.

4. Open the preferred code editor or Jupyter Notebook environment on your local machine and upload the chosen ipynb file there(the prediction you want to perform e.g. flood). Make sure that in the dataset path, paste the path of the downloaded dataset from your local machine (in the case of drought, since the dataset used is very large). For all other models, the dataset is accessed through drive links so there's no need to save the datasets but to give you a basic idea of the data used, I have created a different directory for the datasets.

5. Install the required packages: Check the beginning of each IPython Notebook file for a section that lists the necessary packages and their versions. Install these packages using the appropriate package manager, such as pip. Run the following command for each package you need:
   pip install package_name
   or, ! pip install package_name
   or, ! pip3 install package_name
   
6. All the packages used are mentioned in the start of each prediction model(as import commands). In case you encounter error there, please install the necessary package as per the given command.
   
7. Run the Code: You can now run the code for each prediction model by executing the corresponding Python script or Jupyter Notebook file. Make sure to specify the correct file paths for accessing the datasets.
   
8. Run the notebook cells sequentially to execute the code and generate the predictions for the specific natural disaster category.
   
9. Test the Environment: Run some sample code or test cases to verify that the environment is set up correctly and the models are functioning as expected.
