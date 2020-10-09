# detect-spam-messages
a model to detect spam messages
# Spam Classification App
Spam Classifier uses a logistic regression model to classify messages (preferably SMS) as spam or not spam.

## Prerequisites
Make sure that you have the following:
* Python 3+ and pip (which comes with Python 3+)
* A Unix command line (e.g. Git Bash).

What each file does:
* `server.py` - runs the server and loads the user interface.
* `templates/layout.html` - contains the base HTML
* `templates/index.html` - contains the body of the HTML
* `models/saved/` - contains all locally saved models and dataframes for future loading
* `models/save_df.py` - cleans the dataframe and saves the new dataframe to local file structure.
* `models/model.py` - builds and saves the logistic regression model.
