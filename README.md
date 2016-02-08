This repos is for maintaining my [Cloudformation](https://aws.amazon.com/cloudformation/) templates and [Cumulus](https://github.com/cotdsa/cumulus) stacks

# Cloudformation
To use cloudformation you will need an AWS account with [access keys](http://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey).

# Cumulus
To install Cumulus run the following:
```
pip install cumulus
```

To deploy a stack:
```
cumulus -y filename.yml -a create
```

To destroy a stack:
```
cumulus -y filename.yml -a delete
```

