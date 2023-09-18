# zkcli

Original project: https://github.com/let-us-go/zkcli

A interactive Zookeeper client.

![zkcli](./zkcli.gif)


## Install

```
go install github.com/kyzy540/zkcli@latest
```

## Usage

```shell
$ zkcli ls /test
[abc]
```

```shell
$ zkcli
>>> 
>>> help
get <path>
ls <path>
create <path> [<data>]
set <path> [<data>]
delete <path>
deleteall <path>
connect <host:port>
addauth <scheme> <auth>
close
exit
>>>
```