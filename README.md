# Take me home challenge

## Introduction:
A Data Scientist should possess strong analytical skills as well as experience building software and strong communication skills. This technical challenge covers all three of these components using a sample data set. The data set is about students. The data set includes information about the students’ age, nationality, gender, as well as information about their studying habits. There is also a binary column expressing whether or not the students passed an important test.

This challenge consists of three parts:

### Part 1: Analysis
- Describe the demographic details of people most likely to pass the test
- Describe the efficacy of the two interventions - the test prep course and the Dojo class
- Identify any other interesting trends from the data set and offer some analysis as to their importance or cause.

### Part 2: Model Creation
- Create a model that can predict whether or not a student will pass the test. Use the provided data set to train your model and test its accuracy. You have free choice of programming language, algorithm, and tools.

### Part 3: Reporting
- The goal in the final stage is to communicate your findings to less technical management staff. There are two requirements:
- Create visualizations to show the efficacy of your model. A non-data scientist should be able to infer at a glance how well it fits the data.
- Offer ideas for how we might help more people pass the test and create more accurate models based on your findings. Summarize with bullet points and consider adding more visuals.


## Requirements:
There is a requirements.txt file with a list of all the packages and dependencies you will need.

To install the environment you can use the following commands in the terminal:

```zsh
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

or alternatively, use the Makefile:
```zsh
make setup
source .venv/bin/activate
```

## Files:
The relevant file for this exercise can be found in [take_me_home.ipynb](take_me_home.ipynb)