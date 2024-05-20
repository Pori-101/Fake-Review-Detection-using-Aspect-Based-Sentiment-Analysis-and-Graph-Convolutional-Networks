# Fake-Review-Detection-using-Aspect-Based-Sentiment-Analysis-and-Graph-Convolutional-Networks
This repository contains the code and datasets for the project "Fake Reviews Detection using Aspect-Based Sentiment Analysis." The project aims to detect fake reviews by leveraging aspect-based sentiment analysis and graph convolutional networks.

### Repository Structure

#### Code: 
Contains all the scripts for data processing, model training, and evaluation.

#### Datasets: 
Contains the pre-processed datasets used for training, testing, and validation.

#### Supporting Files: 
Contains configuration files and additional files required for the project.

### Loading Datasets
Make sure to change the paths in the code to load the datasets correctly. For example, update the paths in the scripts to point to the Datasets folder.

### Dataset Pre-processing
All datasets are pre-processed to ensure consistency:
Labels are encoded as 1 (real) and 0 (fake).
Attribute names are standardized across all datasets.
Unnecessary attributes are removed to streamline the data for analysis.

### Required Libraries and Modules
To run the code, you'll need the following libraries and modules installed: \n
pandas \n
numpy \n
scikit-learn \n
torch \n
transformers \n
pickle \n

Install required libraries using pip3 install command

The GloVe 300D text file (glove.6B.300d.txt) is required to run the code. Due to its size, it couldn't be added to the GitHub repository. Please download it separately from the GloVe website.

### Main Code
Make sure you are using Python 3. If CUDA is available, the main code switches to CUDA for faster processing.
The main code creates pickle files and torch objects for easy retrieval and loading in subsequent runs. Change the file paths in the load commands to correctly load them.
All code is structured in Jupyter Notebooks and run on Visual Studio Code.
