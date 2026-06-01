Chapter 1 - Reflections

The first ml application was the email spam filter.

What is Machine Learning ? It is an art of programming computers, so that they can learn from data.

The part of machine learning system that learns from data and predicts is known as model. (Neural Networks, Random Forests)

The working of a ml system is based on finding the patterns from data and make predictions. The spam filter system finds the patterns in the emails marked as spam by the users, starts predictions and flags accordingly.

Digging into large amount of data to discover the hidden patterns is called as Data Mining.

ML is great for
- Problems for existing solutions which requires lot of fine tuning
- Complex Problems where the data fluctuates
- Getting insights on large amount of data


Supervised Learning: The training set that we feed to the algorithm contains the desired solutions. The system learns to predict using training set, adjusts the algorithm if prediction is wrong. Then uses this knowledge to predict for the new unlabelled instance. Classification using regression is a supervised learning.

Unsupervised Learning: The training set doesn't have any labelled data. The system clusters similar data using patterns and this is called as clustering. Useful for extracting features, detecting anomalies. Also helps in visualizing complex data.

Semi-supervised Learning: This is simply clustering and then labelling. Google Photos are good examples of this. Naming one photo is enough after auto grouping.

Reinforcement Learning: Here a agent (learning system) observes the environment, performs actions and gets rewards/penalities in return. Based on the rewards or penality it learns by itself the best strategy. 


The whole process of training, evaluating and launching a ml system is known as MLOps

The important parameter of ML system is learning rate. It is about how fast the system should adapt to the new changing data.
    * If the learning rate is high, the system adapts faster to the new data but forgets the old data.
    * If the learning rate is low, the system learns slowly and also becomes less sensitive to noise in the new data.


What happens if bad data is fed to the system ?

When the bad data enters the system, the system learns from it and the model's performance tends to drop. There must be a moniter to turn off the learning (and possibly revert to old working state) if the model performance drops.


Finally, some main challenges in ML:
- Insufficient quantity of training data
- Poor Quality Data
- Irrelevant Feature Selection
- Overfitting training data
- Underfitting
- Hyperparameter Tuning and Model Selection

EOF :)