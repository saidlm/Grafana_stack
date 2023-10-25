# Grafana_stack
Grafana - Timescaledb - Telegraf stack

### TimescaleDB configuration

* sudo -u postgres createuser --pwprompt grafana
* sudo -u postgres createdb -O grafana -E Unicode -T template0 grafana
