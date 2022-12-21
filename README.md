### Purpose of Orgformation
Setting up a new AWS Account IAM Identity Center:

### Instructions
1. Login to the AWS Account
2. Go to AWS Cloudformation and manually run the `github-identity-provider.yml` template
  1. Should enable OIDC to allow AWS to talk with Github
3. Manually run the cicd pipeline to trigger the Orgformation template
