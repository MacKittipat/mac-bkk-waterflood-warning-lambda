### Install & Configure AWS CLI 
1. Install AWS CLI
2. Create IAM user with Access keys
3. Configure AWS CLI with `aws configure` and enter accessKey/secret

### Serverless Command

```
# Deploy
serverless deploy -v 
# Remove
serverless remove
```

# Credentials

Credentials will be read from `/.aws/credentials`

```
[default]
aws_access_key_id=
aws_secret_access_key=
```