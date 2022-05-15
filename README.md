# Mellifluous Myna

Mellifluous Myna is a machine learning project with an initial aim of creating a model that classifies any music to a suitable genre based on its features. This project makes use of audio feature data from Spotify for training and testing the model.

## First project status meeting is on 17-05-2022 at 16:15 HRS. Please join 5 minutes earlier.

## TODO

### Current

- [x] Create script to fetch audio feature data from Spotify
- [x] Clean data set by removing unnecessary columns
- [x] Select important features using Correlation matrix
- [-] Create stratified test train split of dataset
    - [ ] **(Arnova)** Include statistical evaluation of test and train split
- [-] Create and evaluate Decision Tree model
    - [ ] **(Serkan)** Combine the two notebooks `GenreClassifier_serkan.ipynb` and `GenreClassifier_2_serkan.ipynb` into a single one and rename it to `5_decision_tree.ipynb`
    - [ ] Add headings, comments and author notes and description
- [ ] **(Arnova)** Create and evaluate Random Forest model 
- [ ] **(Adnan)** Create and evaluate Logistic Regression model 
- [ ] **(Soumya)** Create presentation for first status meeting 

### Future

- [ ] Test the ML models
- [ ] Create documentation/Report
- [ ] Write paper

## Updates

### 12-05-2022

- All `csv` files have been moved to data folder and corresponding paths in the notebook files have been updated.
- The notebook names have been numbered in the order of execution.
- Please add author notes and appropriate headings to each section of your code. This will give a general idea about what the following cells are supposed to do. (Refer to any of the notebooks 1 to 3 for an idea)
- Please document your code either using comments or markdown. Everybody codes in different styles and therefore it can be hard to read and understand others' code. Hence provide as much explanation as possible for each function/block of code.
- General things to include in evaluation of all training model:
    + Cross validation accuracy
    + Confusion matrix
    + Precision/Recall
    + ROC/AUC curve
- Other model specific evaluation parameters also needs to be included.

## References

[Spotify API Documentation](https://developer.spotify.com/documentation/web-api/reference/#/)
