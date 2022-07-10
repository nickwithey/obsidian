AWS ACCOUNTS

what is an aws account; Logical container of identities and resources
can the account root user be restricted; No
what are some example usage of AWS accounts; Dev, Prod, Integration, Marketing, Sales, HR
What is special about the Root User Account; First Account created, Has a unique email address, Logon with email address, Full Control over account, Account cannot be restricted
What is IAM; Identity Access Management 
What is IAM used for; Creation of additional identities. None of new identities created have access to any resources unless specifically granted. 
How many accounts is IAM dedicated to ?; One
What rights do user accounts have when created via IAM; No access until specifically granted
What rights do external identities have in AWS Accounts; None unless explicity allowed

MFA 

What is MFA ?; Multi Factor Authentication
What are Factors ?; Pieces of evidence - Knowledge (username/password), Possession (card, virtual token, physical token), inherent (biometrics), location
How does MFA work ?; Secret key is generated based on username / password and combined with resource detail - > QR code is created
How is the QR code used ?; Scanned by mobile device and credentials added to virtual MFA application

BUDGET

What is Cost Explorer ? ; granular view of spends on AWS account 
Billing Prefences ? ; pdf Invoice, Billing Alerts, Free Tier usage
What are Budgets used for ? ;  Managing costs of AWS account(s)
What type of Budgets are available ? ; Cost, Usage, Savings Plan, Reservation
What are the features of a Cost Budget ? ; Monitor spend via alerts






