---
description: >-
  monea-cli is a command line tool for managing, running, and deploying any
  configuration of rollups.
---

# Getting Started

> Please note this CLI is NON-FUNCTIONAL. It is just a basic `println()` demo for what is to come. `monea-cli` WILL not run or deploy any containers on your machine. You can play around at-will.

## Installing

```
brew tap monea-labs/tap
brew install monea-cli
```

## Usage

```
monea --help
```

For more info, view the [CLI reference docs](broken-reference) or check out the [Github Repo](https://github.com/monea-labs/monea-cli).  :)

## Examples

To spin up a local and default Polygon zkEVM CDK chain setup:

```
monea run --execution polygon-cdk
```

To deploy a public cloud optimium L3 (rolls up into Base L2) with Celestia data availability onto Monea Cloud:

```
monea deploy --execution op-stack --data-availability celestia --settlement base
```

To create 2 template setups and run each locally at the same time:

```
monea templates new --name my-first-l2 --execution op-stack --sequencer espresso
monea templates new --name another-l2 --execution op-stack --sequencer based
monea run my-first-l2 my-other-l2
```
