# Enve Labs AWS training
AWS training documentation

#### AWS credentials
How to add credentials to my profile (~/.aws/credentials)?
```
$ aws configure
AWS Access Key ID: ***
AWS Secret Access Key: ***
Default region name [us-east-1]:
Default output format [None]:
```

once added the required information the ~/.aws/credentials file should have a block in init format with the credentials provided
```
[default]
aws_access_key_id = ***
aws_secret_access_key = ***
```

check credentials functionality against AWS API using the `aws` cli command
```
$ aws iam get-user
...
```

```
$ aws sts get-caller-identity
...
```
