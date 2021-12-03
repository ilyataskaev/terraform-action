# Terraform Action

Simple terraform action to run terrafrom on your code

## List of inputs:

| Input | Description | required | Default |
|-------|-------------|----------|---------|
|action|plan, apply or delete|true|n/a|
|app-name|Name of the APP|true|n/a|
|aws-region|AWS Region|false|'us-east-1'|
|aws-access-key-id|AWS Access key ID|true|n/a|
|aws-secret-access-key|AWS Sectret Access key|true|n/a|
|working-directory|Working Directory where to run terraform|false|'./infrastructure'|

