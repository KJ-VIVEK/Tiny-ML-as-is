# Tiny-ML-As-Is
Understanding Tiny-ML concepts as is from Oreilly.

# Machine Learning

- It is technique to predict future things based on past observations.
- ML algorithm builds a model of the system based on the data we provide, through the process called TRAINING.
- Data is run through this model to make predictions called INFERENCE.
- It is a trial and error method, to create a MODEL that gives perfect result, hopefully.
- Machine learning models are good at extracting underlying meaning from messy, real world data.
- Regression: A method where input is "x" and output is "y".
- 


# Deep Learning WorkFlow

The process involves following:
  - Decide on a goal.
    1. Establish what you want to do. WHAT IS THE END GOAL.
  - Collect Dataset.
    1. Select the data, only, that is needed.
    2. Use statistical data to identify which data is significant.
    3. the more data, the better Why? helps establish better relationship between variables, reduction in noise and how class should be distinguished.
    4. Collect the data that covers all conditions and events that can occur.
    5. The data should be in appropriate format for proper training.
    6. the process of associating data with classes is LABELING, and ex: "Normal" & "Abnormal" classes are our LABELS.
  - Design a model architecture.
    1. An architecture is decided based on the problem you are solving.
    2. Understand the device you will be running it on. Tailoring the model to device helps in faster execution cuz, some device might've HW accelerators.
    3. FEATURE is particular type of information on which a models is trained.
    4. Normalising, Windowing, etc, are some methods used on data to bring it to common grounds.
  - Train the mdoel.
    1. Method by which model learns to produce correct output for a given input.
    2. A MODEL is a network of simulated neurons represented by arrays of numbers arranged in layers. These numbers are known as weights and biases or networks parameters.
    3. The MODELS weights start out with random values, and biases start with 0.
    4. An algorithm called "BACKPROPAGATION" adjusts weights and biases incrementally over time, the mdel gets closer to matching the desired value.
    5. Training measure in EPOCHS(iterations), continues until we decide to stop.
    6. Training is stopped when performance sops improving.
    7. When model starts to make accurate predictions, it is said to be CONVERGED. This is done by analysing the graphs of its performace during training.
    8. LOSS metric: shows how far the model is from producing the expected answers. ACCURACY metric: % of correct predictions.
    9. There isn't always enough information within dataset to make accurate predictions, that doesn't mean the model is not useful.
    10.Reason for failure of model to converge: Underfitting(not learned properly) and Overfitting(learnt too much correctly).
    11.Training:60% Validation:20% Test:20% : to make sure, we don't end up making a model under or over fit.
    Terms: Regularization, Data-augmentation,
  - Convert the model: Tensorflow Lite for MCU
  - Run Inference:
    1. We take the model and deploy it on MCU using certain libraries made for MCU.
  - Evaluate and Troubleshoot.

# Understanding Model:
- Activation function is a mathematical function used to shape the output of the neuron.
- Without an activation function, the neurons output would always be a linear function of its input.
- 

# Things to understand:
1. We will need to understand what is happening when a model is being trained.(under the hood)
2. Understand bias and weight values meaning
3. What is an activation function?
4. Understand Quantization
5. 
