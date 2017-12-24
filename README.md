# bip

static IP management via bash

```
bip [-c config=/etc/bip]
```

## Example config

The config is just a simple bash script which sets some variables

```bash
interfaces="eth0 ens8"

eth0_addresses+="10.0.0.1/28 "
eth0_addresses+="10.0.0.11/28"

eth0_routes=("prefix=default via=10.0.0.23")
```
