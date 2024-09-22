# Movie Poster Classifier: ResNet50 for Marketing Insights
This is an initial implementation of a ResNet50-based image classifier designed to analyze movie posters from 1911 to 2005. The goal of this project is to explore applications in the field of marketing, providing insights into how movie poster design strategies can influence and potentially increase box office revenue.

# Project Overview
- Model: ResNet50 pre-trained on ImageNet
- Focus: Analyzing historical movie posters (1911-2005)
- Goal: Identify patterns and design strategies for marketing research

# Getting Started
## Clone the repository
```git clone https://github.com/yourusername/movie-poster-classifier.git```

## Navigate to the project directory
```cd movie-poster-classifier```

## Install necessary dependencies
Have > Python 3.x installed. Jupyter Notebook must be installed as well, along with the required libraries. You can install them using pip:
- Jupyter Notebook:
  ```pip install jupyterlab```
- TensorFlow or PyTorch (for ResNet50):
  ```python3 -m pip install tensorflow``` <br>
  Verify the installation:
  ```python3 -c "import tensorflow as tf; print(tf.reduce_sum(tf.random.normal([1000, 1000])))"```

## Run the Jupyter Notebook:
Open the notebook in Jupyter to run the analysis:
```jupyter notebook movie_poster_classifier.ipynb```

# Future Work
- Fine-tuning the ResNet50 model for better classification accuracy
- Expanding the dataset to include modern movie posters
