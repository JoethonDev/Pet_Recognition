Machine Learning Classification Task

Using Logistic Regression & Kmeans

Dataset : Oxford-iii-pet
Samples : 7349 image
Properties : - 2371 images for cats
             - 4978 images for dogs
             - 37 different class for cats and dogs
             - maximum 200 image per class
             - different image sizes

Preprocessing : 
  0 - Splitting images into dogs and cats
  1 - Get 2 dog classes and 3 cat classes 
  2 - Resizing images to (160, 80)
  3 - Apply greyscale "converting images to black & white"
  4 - Extract features using HOG
  5 - Reshape features list to 2D array
  6 - Splitting features and labels into train and test sets
  

Algorithms : 
  - Logistic Regression Model :
    1 - making model with max_iteration of 1000
    2 - making model with max_iteration of 1000 and solver using liblinear
    fitting both models and appling accuracy_score for checking accuracy

    Optimization :
      1 - Apply Standard Scaler for features
      2 - Train model
      3 - Check accuracy
                              

  - Kmeans Model :
    1 - placing number of cluster to 5
    2 - train model



             
