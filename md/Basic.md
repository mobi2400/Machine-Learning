# Basic
- Artficial Inteligience
    - Machine Learning
        - Deep Learning
- this is the basic flow of AI
- There are two types of data
    - Numerical
        - Age
        - weight
        - CGPA
    - Categorical
        - gender
        - nationality
        - blood group

## Types of Machine learning
- Supervised
    - Regression
    - Clasification
- Unsupervised
    - Clustering
    - Association Rule Learning
    - Dimensionality Reduction
    - Anomaly Detection
- Semi-supervised
- Reinforcement

### Supervised
- when you have a set data with inputs and output
- then ML draw the mathenatical connection between input and output to predict the output for upcoming set of datas

    #### Regression
    - If output data is numerical
    ### Clasification
    - If output data is categorical

### Unsupervised
- when you have only data with inputs

    #### Clustering
    - plottig the graph with the given set of datas
    - categorising the data with some factors
    - and create a label data
    - widely used in industry
    #### Dimensionality Reduction
    - this remove extra inputs coloms which doesnt affect the output data
        - REASON : some time multiple input data makes the algorithm slow when you are working with the textual data to train the model
    - removes the multiple imput coloms and merge them into the new one 
    - PCA algorithm is used for this
    - used when there is N numbers of dimesnsions in data which cannot be plot in 3d or 2d graphs
    #### Anamoly detection
    - To detect something odd
    #### Association rule learning
    - fetch the data and analyze the data and the conclude
    - basically build the relation between the data by recognizing the patterns
### Semisupervised
- It trains models using a small amount of labeled data and a large amount of unlabeled data.
-  This method is particularly useful when it is expensive or time-consuming to obtain a large, fully labeled dataset.
### Reinforcement
- No data is given initially
- It is a trial-and-error process, similar to how humans and animals learn.
- The agent isn't given instructions on what to do; instead, it learns from the consequences of its actions.
- How It Works
    - Agent: The learner or decision-maker (e.g., a robot, a program playing a video game).

    - Environment: The external world the agent interacts with (e.g., a maze, a chess board, a virtual city).

    - State: The current situation or configuration of the environment (e.g., the robot's location in the maze, the position of all chess pieces).

    - Action: A move or decision the agent can make in a given state (e.g., move left, move forward, place a chess piece).

    - Reward: A numerical signal the environment gives the agent after each action. It can be positive (for a good action) or negative (for a bad one). The goal is to maximize the total, long-term reward.

## Other type of Machine learning

### Batch learning
- used all the set of data at once  to train the model
- this is generaly done offline/locally
- once it is trained then you deploy it
- once data is trained and deployed it get static 
- model need to be trained periodically
- Disadvantage
    - Lots of data
    - hardware limitation
    - Availability
### Online learning
- model is trained at server
- data is distributed in small chunk of data and then model is trained by those chunks
- do incremental learning in mini batches sequentially
- when to use
    - where there is a concept drift
    - cost effective
    - faster solution
- River python lib use for online learning
- vowal wabbit python lib use for online learning and for reinforcement learning too
- out of core learning
    - data is so huge that it can not get load
    - so batch learning is used
    - model is trained offline
- problem 
    - risky[corrupted data]
    - tricky

## Types of ML based on how it is learned

### Instance based learning
- plot a graph and find the similarity
- with new data find the similarity with the exisiting data
- similarity is basically distance between them and based on surrounding its judge

### Model based learning
- find mathematical relation between input and output
- based on mathematical equation it judge incoming inputs 
- mostly used in industry
- create A descion function to find the output
- so training point is not needed while drawing the conclusion 


