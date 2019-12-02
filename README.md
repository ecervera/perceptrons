# perceptrons

[Jupyter notebooks](https://jupyter.org/) with exercises of [linear perceptrons](https://en.wikipedia.org/wiki/Perceptron) with [Python](https://www.python.org/) and [scikit-learn](https://scikit-learn.org/).

## Prerequisites

* [Docker](https://docs.docker.com/v17.09/engine/installation/)

## Usage
Run in a terminal:

    git clone https://github.com/ecervera/perceptrons.git
    cd perceptrons
    docker build --rm -t perceptrons .
    docker run -it --rm --volume="$(pwd):/home/jovyan/work:rw" \ 
      -p 8888:8888 perceptrons start.sh jupyter lab --NotebookApp.token=''
      
Open this URL in your favourite browser: [http://localhost:8888/lab/tree/index.ipynb](http://localhost:8888/lab/tree/index.ipynb)
