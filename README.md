# Udacity Cloud DevOps - Course 03

## Deploy a high-availability web app using CloudFormation

### Create infrastructure

- Create network infrastructure

```shell
./create.sh <stack-name> network.yml network-parameters.json
```

- Create server infrastructure

```shell
./create.sh <stack-name> servers.yml server-parameter.json
```

### Update infrastructure

```shell
./update.sh <stack-name> <network|servers>.yml <network|server>-parameters.json
```

### Delete infrastructure

```shell
./delete.sh <stack-name>
```
