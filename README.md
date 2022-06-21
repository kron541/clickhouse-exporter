# clickhouse-exporter

A fork of https://github.com/Altinity/clickhouse-operator/tree/master/cmd/metrics_exporter

```
usage: clickhouse-exporter [<flags>]

Flags:
  -h, --help                   Show context-sensitive help (also try --help-long and --help-man).
      --chi-name="MacBook-Pro.local"
                               Clickhouse cluster name or $HOSTNAME.
      --namespace="default"    The namespace label for metrics or $NAMESPACE.
      --metrics-endpoint=":8888"
                               The Prometheus exporter endpoint.
      --chi-list-endpoint=":8888"
                               The CHI list endpoint.
      --scheme=http            Clickhouse HTTP scheme or $CH_SCHEME
      --username="default"     Clickhouse username or $CH_USERNAME.
      --password=""            Clickhouse user password or $CH_PASSWORD.
      --port=8123              Clickhouse HTTP port number or $CH_PORT.
      --address=127.0.0.1 ...  A list of Clickhouse hosts
      --log-level=info         Only log messages with the given severity or above. Valid levels: [debug, info, warn, error, fatal]
      --log-format=json        Set the log format. Valid formats: [json, text]
      --version                Show application version.
```
