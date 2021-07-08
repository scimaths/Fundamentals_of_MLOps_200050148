### 1. **In the notes of Week 1, we compared & contrasted MLOps with DevOps. In this question, you need to understand what is meant by the term AIOps, & then contrast it with MLOps.**

Gartner Inc coined the term AIOps (Artificial Intelligence for IT Operations). They defined AIOps platforms as using big data and ML technique to enhance IT operations - monitoring, automation and service desk (as is evident from the abbreviation). AIOps Platforms allow usage of many data sources collected using various methods. The overall goal that AIOps tries to fulfull is to streamline the process and minimize human intervention in addressing problems that arise in IT operations.

__Contrasting AIOps and MLOps__ :-<br/>
Even though MLOps and AIOps dwell on Machine Learning as a core part, they serve vastly different purposes. MLOps Practices are used to streamline the usage of ML systems in production while AIOps does the same for IT operations. MLOps tries to make the pathway from collection of data and creation of a model to deployment smooth and continuous while AIOps tends to use such ML systems (made with/without application of MLOps principles) to solve problems that arise in the field of IT in quicker and better way.

### 2. **Interpretable Machine Learning is another concept that has attracted lot of attention recently & is promoted by most of the MLOps frameworks. Explain what it means for a linear regression model to be interpretable. You may find this resource useful.**

Interpretability of a model refers to knowing the "why" for some outcome of the model instead of just knowing the "what" (output) for a model. This can help in understanding both the situation at hand and the model itself.

Interpretation of various parameters can be done for a linear regression model:-<br/>

- Feature -> Changing the feature changes the outcome by a value corresponding to its weight (equivalent to importance) times the amount of change.
- Categorical Features -> These features can be interpreted as options for the model to choose and their respective effects on the outcome.
- Binary Features -> They can be interpreted as affecting the output by virtue of their presence or absence.
- Constant -> This usually doesn't have an interpretation and can be just seen as a transfer of origin for various different cases of weights.