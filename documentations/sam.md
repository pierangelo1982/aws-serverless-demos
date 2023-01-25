# AWS Serverless Application Model (SAM)
[https://aws.amazon.com/it/serverless/sam/](https://aws.amazon.com/it/serverless/sam/)

### installation:
```
wget https://github.com/aws/aws-sam-cli/releases/latest/download/aws-sam-cli-linux-x86_64.zip
```
verify: 

`sha256sum aws-sam-cli-linux-x86_64.zip`

unzip:

`unzip aws-sam-cli-linux-x86_64.zip -d sam-installation`

install aws sam cli:

`sudo ./sam-installation/install`

run:

`sam --version`

### basics

`sam init`

`sam build`

`sam deploy --guided`
