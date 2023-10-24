# Machine Learning 

## End-to-End Learning 
- A deep learning process
- This aims to simplify the traditional machine learning pipeline by integrating all the common steps (feature extraction, data validation, text analysis, cleaning, etc.) in machine learning into a single model.
- This takes on large amounts of raw data and automatically learns from it without the need for human intervention.
- The drawbacks to this approach is that it requires a large amount of data and computational power to train the model. If the dataset is not enough to be able to completely train the model, it is best to result into diving the process into smaller steps then training them individually.

![Example of machine learning pipeline](object-recognition-pipeline.png)
> This is an example of a traditional object recognition pipeline. 
> When it comes to end-to-end, it would only take a single abstracted model, and input and output layer. This removes all of the other steps in the pipeline and automates its process into a single model. 

## Incremental Learning 
- Also known as `online learning`
- A machine learning method where the model is trained on new data over time.
- It is where the model continouously / progressively learns without forgetting previously acquired information.
- This is in contrast to traditional batch learning where the model is trained in a single session and is not updated.

### Catastrophic Forgetting
- A common problem in incremental learning 
- This is when the model forgets the previously / old acquired knolwedge when it learns new information.