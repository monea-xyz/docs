---
description: >-
  Deploys a Docker/K8s instance of the selected options or template to a
  publicly available Monea Cloud instance.
---

# deploy

```basic
$ monea deploy --help
Deploy the Monea command

Usage: monea deploy [OPTIONS] [POSITIONAL_TEMPLATES]...

Arguments:
  [POSITIONAL_TEMPLATES]...  Positional template names

Options:
  -e, --execution <EXECUTION>
          Execution layer [possible values: op-stack, polygon-cdk, arb-orbit, rollkit, polaris]
  -s, --settlement <SETTLEMENT>
          Settlement layer [possible values: local, sepolia, ethereum-mainnet, base]
  -q, --sequencer <SEQUENCER>
          Sequencer [possible values: default, espresso]
  -d, --data-availability <DATA_AVAILABILITY>
          Data availability [possible values: default, celestia, eigen, avail]
  -t, --template <TEMPLATE>
          Template(s)
  -h, --help
          Print help
```
