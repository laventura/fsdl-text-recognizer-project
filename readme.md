# Full Stack Deep Learning Labs

Welcome!

Project developed during lab sessions of the [Full Stack Deep Learning Bootcamp](https://fullstackdeeplearning.com).

- We will build a handwriting recognition system from scratch, and deploy it as a web service.
- Uses Keras, but designed to be modular, hackable, and scalable
- Provides code for training models in parallel and store evaluation in Weights & Biases
- We will set up continuous integration system for our codebase, which will check functionality of code and evaluate the model about to be deployed.
- We will package up the prediction system as a REST API, deployable as a Docker container.
- We will deploy the prediction system as a serverless function to Amazon Lambda.
- Lastly, we will set up monitoring that alerts us when the incoming data distribution changes.

## Schedule for the November 2019 Bootcamp

- First session (90 min)
  - [Setup](setup.md) (10 min): Get set up with jupyterhub.
  - Introduction to problem and [project structure](project_structure.md) (20 min).
  - Gather handwriting data (10 min).
  - [Lab 1](lab1.md) (20 min): Introduce EMNIST. Training code details. Train & evaluate character prediction baselines.
  - [Lab 2](lab2.md) (30 min): Introduce EMNIST Lines. Overview of CTC loss and model architecture. Train our model on EMNIST Lines.
- Second session (60 min)
  - [Lab 3](lab3.md) (40 min): Weights & Biases + parallel experiments
  - [Lab 4](lab4.md) (20 min): IAM Lines and experimentation time (hyperparameter sweeps, leave running overnight).
- Third session (90 min)
  - Review results from the class on W&B
  - [Lab 5](lab5.md) (45 min) Train & evaluate line detection model.
  - [Lab 6](lab6.md) (45 min) Label handwriting data generated by the class, download and version results.
- Fourth session (75 min)
  - [Lab 7](lab7.md) (15 min) Add continuous integration that runs linting and tests on our codebase.
  - [Lab 8](lab8.md) (60 min) Deploy the trained model to the web using AWS Lambda.

### Done
