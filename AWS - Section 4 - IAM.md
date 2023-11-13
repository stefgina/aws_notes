
######################
IAM = identity and acess mnanagement , global service
you apply the least privilledge principle

IAM Roles are for Services (like EC2) where you can add policies (eg. list IAM)

access advisor: says which services are accesed by which users and when (in order to minimise access)
credential report: say things about password usage/change/access keys/MFA etc for all users.

IAM GUIDELINE- BEST PRACTICES

DONT use root account except for AWS account setup
One physical user = One AWS user (dont share acounts)
Assign users to groups and assign permissions
Create a strong password policy (change every 90 days)
Use and enforece MFA
Create and user Roles for AWS services permissions
Use accss keys for programmatic access (SDK)
Audit permission of your account using IAM Credentials Report and IAM access advisor
NEVER SHARE IAM users AND ACCESS KEYS

SHARED Responisibility Model for IAM
AWS: infrastracture, configuration and vulnerability analysis, compliance validation
YOU: Users, groups, roles, policeis, management, monitoring, MFA, rotate all your keys, use IAM tools for permission, analyze access patterns and review permissions

aws is responsible for the infra
you for how you use the infra

IAM SUMMARY:

Users: physical users has a password for AWS Console
Groups: containes users only
Policies: json with permissions
Roles: for EC2 instances or AWS services
Security: MFA + Password policy
AWS CLI: manage aws through command line
AWS SDK: manage your aws using a programmiong language
access keys: access aws using the cli or sdk
audit: IAM Credential Report and IAM Access Advisor



