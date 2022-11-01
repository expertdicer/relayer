## Install go relayer 

[Install Go Relayer here](https://tutorials.cosmos.network/hands-on-exercise/4-ibc-adv/3-go-relayer.html)

## Add chains
Run:

```
$ rly chains add-dir configs
```

## Add paths

```
$ rly paths add-dir paths
```

## Add keys

```
$ rly keys restore checkersa alice "mnemonic"
$ rly keys restore checkersb bob "mnemonic"
```

## Check chains

```
$ rly chains list
```

## Check path

```
$ rly paths list
```