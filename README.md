# Jovia Command Dataset
This repository is home to the dataset that is used to train JoviaAI on interactions with the Godot Game Engine.
The dataset is open source, allowing users to create their own engine actions and submit them to be included in future
fine-tuning of the Jovia model.


## Generating Your Own Training Data
All of the data used in our dataset is generated inside the Godot Engine using our EngineActions plugin.
Follow this link to the EngineActions plugin repository for a guide on how to install and use it.


## Submitting Training Data
To submit your own data to be included in the dataset, create a pull request on this repository using the template below.

```
Description: A short description of the contents of your dataset.
Repository URL: <link to your training data, in its own repository>
```

Once the PR has been opened, it must be reviewed and tested by a member of our team before being merged into this repository.
