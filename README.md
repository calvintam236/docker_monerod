## MoneroD

### What is it?

MoneroD is the console full node & miner provided by [monero-project](https://github.com/monero-project/monero).

MoneroD supports Monero (XMR).

### Example usages

- To build the image:

```console
$ docker build . --file YOUR_VERSION/Dockerfile.YOUR_ARCH --tag calvintam236/monerod:YOUR_VERSION
```

- To run the container in background:

```console
$ docker run -v monerod:/mnt/monerod/ -d --name YOUR_CONTAINER_NAME -p YOUR_PORT_1-YOUR_PORT_3:YOUR_PORT_1-YOUR_PORT_3 calvintam236/monerod:YOUR_VERSION --non-interactive --data-dir /monerod --no-igd --rpc-bind-port YOUR_PORT_1 --rpc-bind-ip 0.0.0.0 --rpc-login YOUR_DAEMON_USERNAME:YOUR_DAEMON_PASSWORD --confirm-external-bind

```

- To get `monerod` options:

```console
$ docker run --rm calvintam236/monerod:YOUR_VERSION
```

- To fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```

### Donations

If you like to buy me a coffee, you can donate to here:

- [Ko-fi](https://ko-fi.com/calvintam236)
- BTC: `1MTkPFtp3qxE4Y98pTHP3z767RGKmrT92a`
- ETH: `0x5896a85E8c175c563DC00087535582394d394838`
- XMR: `474adYsC8sLVM5gK8DbvtUVb237y9m5eMeRuYpJJVuoYUuMN5EYDuixHWxpEr6iNBb2zv3gowmJjcRoTrjhJLvMTRD1eKio`
- ETC: `0xFaBA3be3b3De5469C3F6C6185150928F3773C7b4`
- ZEC: `t1Z5Kc75JQ17txyaDUfwwyabTgsJMfuuSp4`
