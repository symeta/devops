# devops

## table of contents
- [codedeploy](#codedeploy)
- [cloudformation](#cloudformation)
- [secure authorization](#secure-authorization)

## codedeploy
### typical scenario: use codeDeploy to achieve application deployment to EC2 fleet
![Lab2Architecture](https://user-images.githubusercontent.com/97269758/154800945-764998ae-e768-4fe7-bfce-3bb9097441c3.png)

### customer case: use codeDeploy to accomplish cross-region application deployment
codeDeploy uses Tag/deployment group to choose the target ec2 instances
![image](https://user-images.githubusercontent.com/97269758/154800967-875171c8-4b2e-427f-91da-0e0383ab0ac5.png)
![image](https://user-images.githubusercontent.com/97269758/154800971-02529a0a-c9b0-4c11-bc16-bdb36855f4f5.png)

## cloudformation
### changeset

## secure authorization
### leverage on STS assumeRole

### leverage on KMS

### leverage on Parameter Store
