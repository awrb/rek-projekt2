## Recommender Systems - Project 2

This is a project for Recommender Systems class taught by Piotr Zioło, PhD. during the summer semester of 2021 at the Adam Mickiewicz University
(see https://github.com/PiotrZiolo/recommender-systems-class).

The main objective was to train recommenders using a neural network
while trying to achieve the best results possible, based on ranking evaluation measures such as HR@n and NDCG@n.

The project itself consisted of tasks such as:

- preprocessing the data;
- designing optimal features;
- choosing a network architecture;
- experimenting with network parameters such as the number of layers, neurons and activation functions, embeddings, batch sizes;
- tuning the recommenders.

### Running the project

To run the project:

1. Clone the repository and go to its directory;
2. Install the dependencies by preparing a Python 3.8 virtual environment, using a tool such as Anaconda or venv; if using Anaconda you can execute the following in a Bash terminal:

```
conda env create --name rek-project2 -f environment.yml # create the environment
conda activate rek-project2
```

3. Run the Jupyter notebooks with `jupyter-notebook .`