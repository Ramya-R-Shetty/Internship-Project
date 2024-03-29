# Stock Market Prediction Using Machine Learning

### Running for the first time?
*The files environment.yml, requirements.txt make it easy to replicate the environment required for running the model.*
#### Setting up the Environment
1. For anaconda:<br>
   1. To install anaconda, [refer this](https://conda.io/docs/user-guide/install/index.html)<br>
   2. The base directory contains 'environment.yml' file. To replicate the same environment:
      ```bash
      conda env create -f environment.yml
      ```
2. For python3 virtual environment:<br>
   1. To install virtualenv, refer [this](https://www.digitalocean.com/community/tutorials/common-python-tools-using-virtualenv-installing-with-pip-and-managing-packages#a-thorough-virtualenv-how-to)
      ```bash
      pip install virtualenv
      virtualenv --python=python3 ml-stock-prediction
      ```
   2. The base directory contains 'requirements.txt' file. To install the required packages:
      ```bash
      pip install -r requirements.txt
      ```

#### Getting Data
Though the datasets folder has some symbol stock prices. You can populate with more.
```bash
python get_data.py [symbols]
```

#### Running the models
You can run the model on a list of symbols supplied as command line arguments.
```bash
python main.py [symbols]
```
