# Guess Who?

This notebook builds a decision tree that can be used to play a game of Guess Who?. You can run it using Voila to turn it into a standalone web app.

## Getting Started

### Prerequisites

* [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) must be installed on your machine.
* You should have basic knowledge of using Anaconda or Miniconda.

### Installing

1. Clone the repository:
```bash
git clone https://github.com/afvanwoudenberg/guess-who.git
```

2. Navigate into the project folder:
```bash
cd guess-who
```

3. Create the conda environment from the environment.yml file:
```bash
conda env create -f environment.yml
```

4. Activate the conda environment:
```bash
conda activate guess-who
```

5. Start Jupyter Notebook:
```bash
jupyter notebook
```

6. Open Guess Who.ipynb in the browser and run the notebook.

### Using Voila

To turn the notebook into a standalone web app using Voila:

1. Install Voila using conda 
(You can skip this step if you've created an environment from the environment.yml file):

```bash
conda install -c conda-forge voila
```

2. Launch Voila with the notebook:

```bash
voila "Guess Who.ipynb"
```

3. Your web app should now be running at http://localhost:8866/

### Links

Binder file: <a href="https://mybinder.org/v2/gh/afvanwoudenberg/guess-who/main?urlpath=%2Fvoila%2Frender%2FGuess%20Who.ipynb">![Binder](https://mybinder.org/badge_logo.svg)</a>

Blog post: [https://aswinvanwoudenberg.com/posts/how-to-traverse-a-decision-tree-and-win-at-guess-who/](https://aswinvanwoudenberg.com/posts/how-to-traverse-a-decision-tree-and-win-at-guess-who/)

## Image Attribution

The images used in this project are sourced from [https://guesswhocharacters.info/](https://guesswhocharacters.info/). 

## Authors

Aswin van Woudenberg [afvanwoudenberg](https://github.com/afvanwoudenberg)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

