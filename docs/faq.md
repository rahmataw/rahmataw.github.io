## AWS CLI GUIDE

### Prequisition
* Laptop with OS (this guide using OS Ubuntu 16.04)
* Laptop connectivity with internet

### Installation Step
```bash

sudo apt-get update ( ensure OS with latest dependencies)

sudo apt-get install awscli -y

aws --version ( ensure aws cli was installed)aws-cli/1.18.69 Python/3.5.2 Linux/4.15.0-142-generic botocore/1.16.19

aws configure --profile <name>for access key and secret key, you can follow link this here

aws configure --list ( ensure aws profile was added )

aws  sts get-caller-identity ( ensure your credential is working ){   "UserId": "abcdefghijkl",   "Arn": "arn:aws:iam::1234567890:user/user",   "Account": "1234567890"}
```

## Google Cloud SDK GUIDE
### Prequisition
* Laptop with OS (this guide using OS Ubuntu 16.04)
* Laptop connectivity with internet

### Installation Step
```bash
# Update packages
sudo apt-get update ( ensure OS with latest dependencies)

# Download the package
wget https://dl.google.com/dl/cloudsdk/channels/rapid/downloads/google-cloud-sdk-342.0.0-linux-x86_64.tar.gz

# Untar the SDK Package
tar -xvf google-cloud-sdk*

# Install the SDK using install.sh script
./google-cloud-sdk/install.sh

# validate the installation
gcloud --version
```

## SCA GUIDE
### SCA Guidance
[Google Doc](https://docs.google.com/document/d/1AINVTtFfZZ6dIJxSn6NMImCWiLRhYIDdAi4o8VUGPr4/edit#heading=h.kut3tmde557k)
