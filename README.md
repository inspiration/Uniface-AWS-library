# Uniface-AWS-library
Lib of Uniface calls to AWS CLI 
## Pre-req
### AWS CLI
Please download the AWS CLI (windows) toolkit
Setup your profile - located in C:\Users\<your user>\.aws\config

### Uniface
You will need Uniface 9.7

## Notes
The Uniface code can be pasted into a local proc <LPMX> module.
  The DO_PROCESS can receive the AWS IAM (Identity Access Management) group and a list of comma seperated users
  The group will be created if it does not exist.
  The user will be created if they do not exist.
  The user will be added to the group.
  The user will have access key id and secret key created.
  The access key id and secret key can be handled in the TODO section of the DO_PROCESS module
