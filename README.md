## MoneroD

### What is it?

MoneroD is the console full node & miner provided by [monero-project](https://github.com/monero-project/monero).

MoneroD supports Monero (XMR).

### Example usages

Replace `ARCH` for your graphic card architecture. Available option(s): `x86_64`, `aarch64`

- To run the container in background:

```console
$ docker run -v monerod:/monerod -d --name YOUR_CONTAINER_NAME -p YOUR_PORT_1-YOUR_PORT_3:YOUR_PORT_1-YOUR_PORT_3 calvintam236/monerod:x86_64 --non-interactive --data-dir /monerod --no-igd --rpc-bind-port YOUR_PORT_1 --rpc-bind-ip 0.0.0.0 --rpc-login YOUR_DAEMON_USERNAME:YOUR_DAEMON_PASSWORD --confirm-external-bind
```

- Get `monerod` options:

```console
$ docker run --rm calvintam236/monerod:ARCH
```

- To fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```

### Donations

If you like to buy me a cup of coffee for this Dockerfile/ docker image, you can donate to here:

- BTC: `1MTkPFtp3qxE4Y98pTHP3z767RGKmrT92a`
- ETH: `0x5896a85E8c175c563DC00087535582394d394838`
- XMR: `4ASikgNhKqmY5EjnaoDws1jjyhQy9ZrcDcCwfYVt5Rtxb6B1FqsehpLY8ZxxZD5B6r8QZKb4y1FKW1eqiS5Lph77Ca9qprU`
- ETC: `0xFaBA3be3b3De5469C3F6C6185150928F3773C7b4`
- ZEC: `t1Z5Kc75JQ17txyaDUfwwyabTgsJMfuuSp4`
