# Freqtrade

This a sample Freqtrade bot with basic trading strategies.

# How to run

In order to run docker use the command:

```shell
docker-compose up
```

# Commands Info

Docker has its own command line, so run freqtrade commands inside docker's shell using:

```shell
docker exec -it freqtrade bash
```

# How to test

In order to backtest a strategy you need to download history data using this command:

```shell
freqtrade download-data --timeframe <your timeframe> --timerange <your timerange like: 20220101-20220714>
```
