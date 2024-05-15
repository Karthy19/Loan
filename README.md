# Loan Approval Application
The objective of this Machine Learning project is to build a model and web application that the bank can use to classify if a user can be granted a loan or not.

Deployed link: 



## Endpoints

1. `/home`: Home page
2. `/prediction`: Prediction form
3. `/result`: API
    - Return: `[pred_prob, pred_class]`
   

## Project Structure

- Folders:
    - `dev`: development scripts
    - `models`: pickled pre-trained model (scikit-learn pipeline)
    - `static`: css files
    - `template`: html files

- Application Files:
    - `app.py`: main application
    - `forms.py`: wtforms class

- Deployment Files:
    - `requirements.txt`: package dependencies
    
## Dependencies

The app is built using Python 3.12.1, with the following dependencies:

- `Flask`: web framework
- `Flask-WTF`: forms validation
- `pandas`: data analysis
- `scikit-learn`: model pipeline


List of dependencies and its version can be found on `requirements.txt`.

## Future Improvement Ideas

- Improve classifier performance
- Create new page for batch prediction, using upload and download file
- Create new page for explainable results, using LIME or SHAP
