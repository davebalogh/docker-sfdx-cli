## Docker SFDX Cli

Using [docker](https://docs.docker.com/get-started/) to run [sfdx cli](https://developer.salesforce.com/tools/sfdxcli).

Lightweight Docker image using alpine.

**Setup**

```shell
git clone git@github.com:davebalogh/docker-sfdx-cli.git

cd docker-sfdx-cli 

docker build -t docker-sfdx-cli --no-cache .

docker run -it -v $(pwd):/projects docker-sfdx-cli
```
