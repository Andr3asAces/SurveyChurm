# SurveyChurm

This dataset is a subset of an active survey panel. 

Collected from 3 data sources a customer management database a survey management database and an email tracker software tool.

The data has been preprocessed and cleaned. Some features have been removed on purpose and some feature engineering has been performed already.

The goal it to predict whether a survey participant is likely to unsubscribe.


- RowIndex            = Each row represents a survey participant aka contact of an account.
- Churn               = 0 for Active 1 for Unsub 
- Surveys - Paused On = 0 receiving surveys 1 not receiving 
- Survey Tag          = Survey type

Account information the participant belongs to. Each Account is a paid customer to the survey business.

- Region              = uk region
- Account Type        = type of the account member, target or stakeholder
- Account Value       = value of the account this year 

Emails tracked per participant.

- Clicks_sum          = total number of clicks
- Deliveries_sum      = total number of emails
- Opens_sum           = total number of opening the email


- Time since response = How many days past since last response.    
