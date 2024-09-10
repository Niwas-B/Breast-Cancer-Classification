<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breast Cancer Classification Using Logistic Regression</title>
</head>
<body>
    <h1>Breast Cancer Classification Using Logistic Regression</h1>

    <p>
        This project implements a Logistic Regression model to classify breast cancer cases using the provided dataset 
        (<code>breast_cancer.csv</code>). The model is trained and evaluated using Python libraries such as <code>pandas</code>, 
        <code>numpy</code>, and <code>scikit-learn</code>.
    </p>

    <h2>Project Overview</h2>
    <p>
        The objective of this project is to predict whether a breast cancer tumor is malignant or benign using logistic regression. 
        The dataset is split into training and test sets, and various evaluation metrics are calculated, including accuracy and 
        cross-validation scores.
    </p>

    <h2>Dataset</h2>
    <p>
        The dataset used in this project is <code>breast_cancer.csv</code>. It contains several features related to breast cancer 
        tumors and a target column indicating whether the tumor is malignant (1) or benign (0).
    </p>

    <h2>Libraries Used</h2>
    <ul>
        <li><code>pandas</code>: For data manipulation.</li>
        <li><code>numpy</code>: For numerical operations.</li>
        <li><code>matplotlib</code>: For plotting (if any).</li>
        <li><code>scikit-learn</code>: For machine learning and evaluation.</li>
    </ul>

    <h2>Steps Involved</h2>
    <ol>
        <li><strong>Data Loading and Preprocessing:</strong>
            <p>
                The dataset is loaded using <code>pandas</code>, and the target and feature columns are separated. 
                The data is split into training and testing sets using <code>train_test_split</code>.
            </p>
        </li>
        <li><strong>Model Training:</strong>
            <p>A logistic regression model is trained on the training set.</p>
        </li>
        <li><strong>Model Evaluation:</strong>
            <p>Predictions are made on the test set. A confusion matrix is calculated. 
                Cross-validation is performed to assess model performance with 10-fold cross-validation.
            </p>
        </li>
    </ol>

    <h2>Model Performance</h2>
    <p><strong>Accuracy:</strong> 96.70%</p>
    <p><strong>Standard Deviation:</strong> 1.96%</p>

    <h3>Confusion Matrix:</h3>
    <pre>
[[84  3]
 [ 3 77]]
    </pre>

    <h2>How to Run</h2>
    <ol>
        <li>Clone this repository:</li>
        <pre><code>git clone https://github.com/your-username/breast-cancer-logistic-regression.git</code></pre>

        <li>Install required dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>

        <li>Run the Jupyter notebook:</li>
        <pre><code>jupyter notebook</code></pre>

        <li>Execute the notebook cells to train the model and evaluate performance.</li>
    </ol>

    <h2>Future Work</h2>
    <p>
        Tune hyperparameters to improve model performance. 
        Experiment with other machine learning models such as Decision Trees or SVMs.
    </p>
</body>
</html>
