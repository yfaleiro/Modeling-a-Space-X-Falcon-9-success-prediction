# Space X Falcon 9 first land success prediction

## Context and objective

In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Used libraries

Most of the work was done using the following libraries: pandas, numpy, matplotlib, seaborn and sklearn.

## Methodology and results

After the data collection, I did a standard data cleaning and wrangling before developing a model. After that, I tried to find which type of model would work best for my purpose. I developed and tested four types of models: logarithmic regression, support vector machines, decision tree and k-nearest neighbors. The graph below shows which model performed better and should be used to predict the Falcon 9 first land success:
![image](https://github.com/yfaleiro/Modeling-a-Space-X-Falcon-9-success-prediction/assets/116303455/9cf57cae-c812-442a-be58-faa3f09305f4)
