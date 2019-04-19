# aws-sam-template

[AWS SAM](https://github.com/awslabs/serverless-application-model) development template for my machine.


# Using

https://github.com/cnadiminti/docker-aws-sam-local


# Usage

1. execute
```bash
$ docker-compose up -d
Creating network "aws-sam-template_default" with the default driver
...
Creating aws-sam-template_dynamodb_1      ... done
Creating aws-sam-template_aws-sam-local_1 ... done
```

1. execute SAM commands.
```bash
$ docker-compose run aws-sam-local <command here>
```

# Reference

https://dev.classmethod.jp/cloud/aws/20170816-sam-local/
https://hub.docker.com/r/amazon/dynamodb-local/

