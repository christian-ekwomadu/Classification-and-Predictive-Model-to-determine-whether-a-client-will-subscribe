# Classification-and-Predictive-Model-to-determine-whether-a-client-will-subscribe to long term deposit.

# INSTALLATIONS NEEDED:
•Jupyter Notebook Link to instructions on installing and using Jupyter Notebook: https://test-jupyter.readthedocs.io/en/latest/install.html

# Data Source and Data Preparation:
Data Source: https://www.kaggle.com/datasets/rashmiranu/banking-dataset-classification

Data was obtained from direct marketing campaigns from this bank. This information is from phone call surveys, in which clients were asked if they would subscribe to a bank term deposit. The dataset created captures 21 inputs about a given client.

Original Format: comma-separated values (CSV)

# Relevant Variables and Details:
•Age (numeric): The age of the Client
•Job (Categorical, nominal): The Job of the Client
•Marital: Marital Status of the Client. ('divorced',
'married', 'single', 'unknown'; note: 'divorced' means divorced or widowed)
•Default (categorical, nominal): has credit in
default? ('no', 'yes', 'unknown')
•Loan: has personal loan? ('no', 'yes', 'unknown')
•Housing: has housing loan? ('no', 'yes', 'unknown')
•Contact (categorical, nominal): contact
communication type ('cellular', 'telephone')
•Month (categorical, ordinal): last contact month of
year ('Jan', 'Feb', 'Mar', …, 'Nov', 'Dec')
•Dayofweek (categorical, ordinal): last contact day of
the week ('Mon', 'Tue', 'wed', 'Thu', 'Fri')
•Duration(numeric): last contact duration, in seconds . Important note: this
attribute highly affects the output target (e.g., if duration=0 then
y='no')
•Campaign(numeric): number of contacts performed during this campaign and for
this client (includes last contact)
•Pdays (numeric): number of days that passed by
after the client was last contacted from a previous campaign (999 means
client was not previously contacted)
•Previous
(numeric): number of contacts performed before this campaign and for
this client
•Poutcome (Categorical, nominal): outcome of the
previous marketing campaign ('failure', 'nonexistent', 'success')
•Y(binary): has the client subscribed a term deposit? ('yes', 'no')





