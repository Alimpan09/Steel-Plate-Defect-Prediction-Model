# Steel-Plate-Defect-Prediction-Model
Using different Machine Learning Model, It is a trained prediction model which can predict Lung Cancer by taking various features as input with approximately 90% accuracy.
# Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Steel Plates Faults dataset from UCI. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

# Files
train.csv - the training dataset; there are 7 binary targets: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults
test.csv - the test dataset; your objective is to predict the probability of each of the 7 binary targets
sample_submission.csv - a sample submission file in the correct format
# Features’ description:
X_Minimum: The minimum x-coordinate of the bounding box of the defect.
X_Maximum: The maximum x-coordinate of the bounding box of the defect.
Y_Minimum: The minimum y-coordinate of the bounding box of the defect.
Y_Maximum: The maximum y-coordinate of the bounding box of the defect.
Pixels_Areas: The total number of pixels in the defect area.
X_Perimeter: The perimeter of the defect in the x-direction.
Y_Perimeter: The perimeter of the defect in the y-direction.
Sum_of_Luminosity: The sum of luminosity values in the defect area.
Minimum_of_Luminosity: The minimum luminosity value in the defect area.
Maximum_of_Luminosity: The maximum luminosity value in the defect area.
Length_of_Conveyer: The length of the conveyer where the defect was detected.
TypeOfSteel_A300: Binary indicator for type of steel A300.
TypeOfSteel_A400: Binary indicator for type of steel A400.
Steel_Plate_Thickness: Thickness of the steel plate.
Edges_Index: Index indicating the ratio of the total length of edges to the perimeter.
Empty_Index: Index indicating the ratio of empty spaces to the defect area.
Square_Index: Index indicating the ratio of the square of perimeter to the defect area.
Outside_X_Index: Index indicating the ratio of the number of exterior contours to the defect area in the x-direction.
Edges_X_Index: Index indicating the ratio of the number of edges in the x-direction to the defect area.
Edges_Y_Index: Index indicating the ratio of the number of edges in the y-direction to the defect area.
Outside_Global_Index: Index indicating the ratio of the number of exterior contours to the defect area globally.
LogOfAreas: The logarithm of the defect area.
Log_X_Index: Index indicating the ratio of the logarithm of the defect area to the defect length in the x-direction.
Log_Y_Index: Index indicating the ratio of the logarithm of the defect area to the defect length in the y-direction.
Orientation_Index: Index indicating the orientation of the defect.
Luminosity_Index: Index indicating the luminosity of the defect.
SigmoidOfAreas: Sigmoid transformation of the defect area.
Pastry: Binary indicator for the presence of a pastry defect.
Z_Scratch: Binary indicator for the presence of a Z scratch defect.
K_Scatch: Binary indicator for the presence of a K scratch defect.
Stains: Binary indicator for the presence of stains.
Dirtiness: Binary indicator for the presence of dirtiness.
Bumps: Binary indicator for the presence of bumps.
Other_Faults: Binary indicator for the presence of other faults.
# Models used
Logistic Regression, RandomForestClassifier, ExtraTreesClassifier,LGBMClassifier, XGBClassifier,CatBoostClassifier,MultiOutputClassifier
# Submission File
For each id in the test set, you must predict the probability for each of 7 defect categories: Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults. 
# Kaggle Notebook Link:
https://www.kaggle.com/code/abhishekkumar2111/steel-plate-defect-prediction-model/notebook

