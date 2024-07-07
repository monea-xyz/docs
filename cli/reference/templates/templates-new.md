---
description: Creates a new template with any option, and gives it a name.
---

# templates new

```bash
$ monea templates new --help
Create a new template

Usage: monea templates new [OPTIONS] --name <NAME>

Options:
  -n, --name <NAME>
          Template name
  -e, --execution <EXECUTION>
          Execution layer [possible values: op-stack, polygon-cdk, arb-orbit, rollkit, polaris]
  -s, --settlement <SETTLEMENT>
          Settlement layer [possible values: local, sepolia, ethereum-mainnet, base]
  -q, --sequencer <SEQUENCER>
          Sequencer [possible values: default, espresso]
  -d, --data-availability <DATA_AVAILABILITY>
          Data availability [possible values: default, celestia, eigen, avail]
  -h, --help
          Print help
```
