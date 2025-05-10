# AWS CLI

>Configure aws cli by creating access key and secret for IAM User and configure in CLI

`
aws configure
`
### Get the secrets
```
aws secretsmanager get-secret-value --secret-id app/folder/env --output text
```

