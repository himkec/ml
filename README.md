

# Machine Learning

## What is Machine Learning?

In basic terms, ML is the process of training a piece of software, called a model, to make useful predictions or generate content from data.

## Types of ML Systems
ML systems fall into one or more of the following categories based on how they learn to make predictions or generate content:

- Supervised learning
- Unsupervised learning
- Reinforcement learning
- Generative AI

### Supervised learning
Supervised learning models can make predictions after seeing lots of data with the correct answers and then discovering the connections between the elements in the data that produce the correct answers. This is like a student learning new material by studying old exams that contain both questions and answers. Once the student has trained on enough old exams, the student is well prepared to take a new exam. These ML systems are "supervised" in the sense that a human gives the ML system data with the known correct results.

```
                                        Supervised learning
                                                  |
                                                  |
                         ---------------------------------------------
                         |                                           |
                    Regression                                Classification
                                                                     |
                                                ----------------------------------
                                                |                                |
                                       Binary Classification        Multiclass Specification 


```

#### Regression
A regression model predicts a numeric value. For example, a weather model that predicts the amount of rain, in inches or millimeters, is a regression model.


| Scenario   | Possible input data   | Numeric prediction  |
|------------|-----------------------|---------------------|
| Future house price | Square footage, zip code, number of bedrooms and bathrooms, lot size, mortgage interest rate, property tax rate, construction costs, and number of homes for sale in the area. | The price of the home.|
| Future ride time | Historical traffic conditions (gathered from smartphones, traffic sensors, ride-hailing and other navigation applications), distance from destination, and weather conditions. | The time in minutes and seconds to arrive at a destination. |

#### Classification
Classification models predict the likelihood that something belongs to a category. Unlike regression models, whose output is a number, classification models output a value that states whether or not something belongs to a particular category. For example, classification models are used to predict if an email is spam or if a photo contains a cat.

Classification models are divided into two groups: binary classification and multiclass classification. Binary classification models output a value from a class that contains only two values, for example, a model that outputs either rain or no rain. Multiclass classification models output a value from a class that contains more than two values, for example, a model that can output either rain, hail, snow, or sleet.

### Unsupervised learning
Unsupervised learning models make predictions by being given data that does not contain any correct answers. An unsupervised learning model's goal is to identify meaningful patterns among the data. In other words, the model has no hints on how to categorize each piece of data, but instead it must infer its own rules.








### Supervised Learning
Supervised learning's tasks are well-defined and can be applied to a multitude of scenarios—like identifying spam or predicting precipitation.

#### Foundational supervised learning concepts
Supervised machine learning is based on the following core concepts:

- Data
- Model
- Training
- Evaluating
- Inference

#### Data
Data is the driving force of ML. Data comes in the form of words and numbers stored in tables, or as the values of pixels and waveforms captured in images and audio files. We store related data in datasets. For example, we might have a dataset of the following:

- Images of cats
- Housing prices
- Weather information

Datasets are made up of individual examples that contain features and a label. You could think of an example as analogous to a single row in a spreadsheet. Features are the values that a supervised model uses to predict the label. The label is the "answer," or the value we want the model to predict. In a weather model that predicts rainfall, the features could be latitude, longitude, temperature, humidity, cloud coverage, wind direction, and atmospheric pressure. The label would be rainfall amount.

Examples that contain both features and a label are called labeled examples.

In contrast, unlabeled examples contain features, but no label. After you create a model, the model predicts the label from the features.

#### Dataset characteristics
A dataset is characterized by its size and diversity. Size indicates the number of examples. Diversity indicates the range those examples cover. Good datasets are both large and highly diverse.

Some datasets are both large and diverse. However, some datasets are large but have low diversity, and some are small but highly diverse. In other words, a large dataset doesn’t guarantee sufficient diversity, and a dataset that is highly diverse doesn't guarantee sufficient examples.

For instance, a dataset might contain 100 years worth of data, but only for the month of July. Using this dataset to predict rainfall in January would produce poor predictions. Conversely, a dataset might cover only a few years but contain every month. This dataset might produce poor predictions because it doesn't contain enough years to account for variability.
