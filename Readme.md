Cellpose
Report:

### Day One:

#### Steps:

0) Handle the error about generating HTML and write it to PDF.
1) Try to run the previous code and create a model based on the previous dataset
2) Commit and Push the codes to GitHub in a new organization and new branches
3) Upload the new dataset for the test section and try to measure the model on a new data set


#### Results:
1) First try and first result with just 3 images:
|   | Image           | Prediction v. GT IoU | FP | TP | FN | Precision | Recall | Accuracy | F1 |
|---|------------------|------------------------|----|----|----|-----------|--------|----------|----|
| 0 | cb13cb5f85.png   | 0                      | 0  | 0  | 2  | 0         | 0      | 0        | 0  |
| 1 | cc9540d282.png   | 0                      | 0  | 0  | 3  | 0         | 0      | 0        | 0  |
| 2 | cc87926397.png   | 0.53515                | 3  | 16 | 1  | 0.842105  | 0.941176 | 0.8      | 0.888889  |

## Bugs:
1) 




