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

IAM - BASICS

What is a critical piece of any user rights granted ?; Least privilege access
What 3 features does IAM provide ?; Users, Groups and Applications
What are the 3 functions of IAM ?; Identity Provider, Authorisation, Authentication
Is IAM resilient ?; Yes - globally resilient - available across all regions
What are IAM users ?; individually identified user accounts (humans or apps)
What are IAM groups ?;Collections of related users
What are IAM Roles ?;Used by AWS services, Grant external access - Grants to uncertain number of entities
How are IAM policies used ?; Allow / deny access to resources, Must be attached to other identities
What can IAM not do ?; Have any control over external users /accounts (Can use ID Federation / MFA)
What are the 2 types of IAM User credential ?;Access key and AWS console access
What are IAM Access Keys used for ?;Accessing AWS via command line / API
What are IAM long term credentils ?; Credentials that don't change regularly and ones that the user has to change.
Which type of IAM security principal does not use Access 





