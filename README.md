# What is MoneroD?

MoneroD is the console full node & miner provided by [monero-project](https://github.com/monero-project/monero).

# How to use this image

Create shared volume:

```console
$ docker volume create --name monerod
```

Run in background:

```console
$ docker run -v monerod:/monerod -d --name YOUR_CONTAINER_NAME -p YOUR_PORT_1-YOUR_PORT_3:YOUR_PORT_1-YOUR_PORT_3 calvintam236/monerod --data-dir /monerod --no-igd --rpc-bind-port YOUR_PORT_1 --rpc-bind-ip 0.0.0.0 --rpc-login YOUR_USERNAME:YOUR_PASSWORD --confirm-external-bind
```

Get `monerod` options with:

```console
$ docker run --rm calvintam236/monerod
```

Fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
