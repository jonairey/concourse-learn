# concourse-learn

Following instructions at https://concourse-ci.org/docs.html

## Setup

```
# Spin up Concourse
brew install wget
wget https://concourse-ci.org/docker-compose.yml
docker-compose up -d

# Setup fly
# Go to http://localhost:8080 and download fly to git root by clicking OS link
chmod +x ./fly
./fly -t tutorial login -c http://localhost:8080 -u test -p test
