# recommend-phone-subscriptions
My first ML project. Don't look 🙈!

## Project description

Project description Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. We have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan with the highest possible accuracy.

## Project instructions
    Open and look through the data file. Path to the file:datasets/users_behavior.csv Download dataset
    Split the source data into a training set, a validation set, and a test set.
    Investigate the quality of different models by changing hyperparameters. Briefly describe the findings of the study.
    Check the quality of the model using the test set.
    Additional task: sanity check the model. This data is more complex than what you’re used to working with, so it's not an easy task. We'll take a closer look at it later.

## Data description
### *users_behavior.csv*
<ul>
  <li><i>сalls</i></li> - number of calls
  <li><i>minutes</i></li> - total call duration in minutes
  <li><i>messages</i></li> — number of text messages
  <li><i>mb_used</i></li> — Internet traffic used in MB
  <li><i>is_ultra</i> — plan for the current month (Ultra - 1, Smart - 0)
</ul>
 
