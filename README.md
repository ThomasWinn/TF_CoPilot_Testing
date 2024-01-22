# TF_CoPilot_Testing
TensorFlow CNN Image Classification Environment to evaluate the effectiveness of using the GitHub CoPilot tool. In this test, we will be testing the completion time and reliability of the GitHub CoPilot tool to argue productivity increases amongst AI developers.

## Setup
Please download the Fruit-360 Kaggle dataset [here](https://www.kaggle.com/datasets/moltean/fruits).

Please branch off from this main branch when developing. 

We will all be controlling the environment setup using Python 3.10.
```bash
conda create -y -n copilot_eval python=3.10
conda activate copilot_eval
```

Next, we will install the requirements.
```bash
pip install -r requirements.txt
```

The way evaluators should be able to run your code is by calling a main.py file to get rid of any confusion of entry point of code. For example, all branches should be ran using the following:
```bash
python main.py
```

## Results
Please record your results of how long it took you to do your exercise.

Did you use GitHub CoPilot? Y/N

How long did it take to complete this roughly? _hrs, _mins

If you were using GitHub CoPilot, how many suggestions did you use when using the autocomplete feature? _ / NA

If you were using GitHub CoPilot, how many wrong suggestions failed to work when using the autocomplete feature? _ / NA
