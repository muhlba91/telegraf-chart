# Telegraf Helm Chart

[![](https://img.shields.io/github/license/muhlba91/telegraf-chart?style=for-the-badge)](LICENSE)
[![](https://img.shields.io/github/workflow/status/muhlba91/telegraf-chart/Helm?style=for-the-badge)](https://github.com/muhlba91/telegraf-chart/actions)
[![](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/telegraf)](https://artifacthub.io/packages/search?repo=telegraf)
<a href="https://www.buymeacoffee.com/muhlba91" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="28" width="150"></a>

A Helm chart for [Telegraf](https://github.com/influxdata/telegraf).

---

## Installation Notes

Please take a look at the [`values.yaml`](charts/telegraf/values.yaml) file for customization.

You can install the chart with Helm like this:

```bash
helm repo add telegraf https://muhlba91.github.io/telegraf-chart
helm install telegraf telegraf/telegraf -f values.yaml
```

---

## Configuration

Please refer to [https://hub.docker.com/_/telegraf/](https://hub.docker.com/_/telegraf/) on how to configure the container.

---

## Contributing

We welcome community contributions to this project.

## Supporting

If you enjoy the application and want to support my efforts, please feel free to buy me a coffe. :)

<a href="https://www.buymeacoffee.com/muhlba91" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="75" width="300"></a>
