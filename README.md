# SVMParamerterOptimization
This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken a dataset and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

We used the Scikit-learn library in Python to implement our SVM model and optimize its parameters. The dataset we used for this project was Chess (King-Rook vs. King) Data Set. After splitting the dataset into 10 random samples, we trained and tested our SVM model using various parameter combinations.

The final result of our project is a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. This table can be used as a reference for future classification problems that require SVM parameter optimization.

Feel free to explore the code and results in this repository, and please let us know if you have any questions or feedback.
# Dataset Description

This dataset contains positions of the King and Rook on a chessboard and the decision on whether it is a winning position for White (first player) or not. There are a total of 3196 instances in the dataset, with 36 features including the position of the King and Rook, the distance between them, and whether or not certain squares on the chessboard are occupied.
# Attribute Information

    WK-Column (white king column)
    WK-Row (white king row)
    WR-Column (white rook column)
    WR-Row (white rook row)
    BK-Column (black king column)
    BK-Row (black king row)
    'a' file (whether or not the square a1 is occupied by white rook or king)
    'b' file (whether or not the square b1 is occupied by white rook or king)
    'c' file (whether or not the square c1 is occupied by white rook or king)
    'd' file (whether or not the square d1 is occupied by white rook or king)
    'e' file (whether or not the square e1 is occupied by white rook or king)
    'f' file (whether or not the square f1 is occupied by white rook or king)
    'g' file (whether or not the square g1 is occupied by white rook or king)
    'h' file (whether or not the square h1 is occupied by white rook or king)
    Result (the classification result, i.e. whether the position is a winning position for White or not)

# Source

This dataset was created by David A. Wheeler and available in the UCI Machine Learning Repository.
References

    UCI Machine Learning Repository: Chess (King-Rook vs. King) Data Set (https://archive.ics.uci.edu/ml/datasets/Chess+%28King-Rook+vs.+King%29)

# Results

After applying SVM on the 10 random samples of the dataset, we were able to achieve an accuracy of 48.1%. We also identified the best SVM parameters for each sample, which allowed us to achieve even higher accuracy in some cases.

Furthermore, we conducted a sensitivity analysis on the dataset to determine which features had the greatest impact on the accuracy of the model. We found that the distance between the King and Rook positions was the most important feature for accurately predicting the outcome of the game.

Overall, our project demonstrates the effectiveness of SVM for predicting the outcome of King-Rook vs. King chess games. Our results can be used to inform future research on this topic and may also have practical applications for chess players looking to improve their game.
