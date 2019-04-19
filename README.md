# aws-sam-template

[AWS SAM](https://github.com/awslabs/serverless-application-model) development template for my machine.


# Using

https://github.com/cnadiminti/docker-aws-sam-local


# Usage


run sam command.

```
docker run -it --rm \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v "$(pwd)":/var/opt \
    -p "3000:3000" \
    cnadiminti/aws-sam-local {any command}
```

note: `-v /var/run/docker.sock:/var/run/docker.sock`はdocker内でLambdaのDockerを起動するために必要.

# Reference

https://dev.classmethod.jp/cloud/aws/20170816-sam-local/


