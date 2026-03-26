---
title: Quick Start with TiDB Self-Managed
summary: Learn how to quickly get started with TiDB Self-Managed using TiUP playground and see if TiDB is the right choice for you.
aliases: ['/docs/dev/quick-start-with-tidb/','/docs/dev/test-deployment-using-docker/']
---

# Quick Start with TiDB Self-Managed

Choose the fastest TiDB Self-Managed path based on your goal, environment, and the depth of evaluation you need.

This page helps you:

- try TiDB locally in minutes
- explore the core TiDB components and endpoints
- simulate a more realistic self-managed deployment flow
- move to the right next step after evaluation

> **Note:**
>
> The methods provided on this page are **ONLY FOR** quick start. They are **NOT FOR** production deployment or comprehensive functionality and stability testing.
>
> - To deploy a self-hosted production cluster, see the [production installation guide](/production-deployment-using-tiup.md).
> - To deploy TiDB on Kubernetes, see [Get Started with TiDB on Kubernetes](https://docs.pingcap.com/tidb-in-kubernetes/stable/get-started).
> - To manage TiDB in the cloud, see [TiDB Cloud Quick Start](https://docs.pingcap.com/tidbcloud/tidb-cloud-quickstart).

## Pick your quick start path

<DocHomeCardContainer>

<DocHomeCard href="#deploy-a-local-test-cluster" label="Try TiDB locally" icon="oss-getstarted-blue">

The fastest path for first-time users who want to run TiDB on macOS or Linux in 5 to 10 minutes.

</DocHomeCard>

<DocHomeCard href="#simulate-production-deployment-on-a-single-machine" label="Simulate production deployment" icon="oss-deploy-blue">

A more realistic self-managed deployment flow on a single Linux server for deeper evaluation in 15 to 20 minutes.

</DocHomeCard>

<DocHomeCard href="https://play.tidbcloud.com/?utm_source=docs&utm_medium=tidb_quick_start" label="Try TiDB Playground" icon="global-tidb-playground">

Explore TiDB in the browser without installing anything locally.

</DocHomeCard>

</DocHomeCardContainer>

## Not sure which path to choose?

Choose **Try TiDB locally** if you want to:

- get TiDB running as quickly as possible
- learn the basics of TiDB components and cluster endpoints
- evaluate TiDB on a macOS or Linux development machine

Choose **Simulate production deployment** if you want to:

- understand a more realistic self-managed deployment workflow
- validate machine requirements and topology concepts
- prepare for a later move to the full production installation guide

If you want a managed experience instead of self-managed deployment, use [TiDB Cloud Quick Start](https://docs.pingcap.com/tidbcloud/tidb-cloud-quickstart). If you want a browser-based trial, use [TiDB Playground](https://play.tidbcloud.com/?utm_source=docs&utm_medium=tidb_quick_start).

## Compare the quick start paths

| Path | Best for | Environment | Time | Complexity | Outcome |
| :-- | :-- | :-- | :-- | :-- | :-- |
| Try TiDB locally | First-time users, developers, architecture exploration | macOS or Linux | 5-10 min | Low | A local TiDB cluster with Dashboard and monitoring endpoints |
| Simulate production deployment | Operators, DBAs, deeper evaluation | Linux only | 15-20 min | Medium | A minimal full-topology TiDB cluster on one machine |
| TiDB Playground | Fast feature exploration, demos, zero setup | Browser | 1-3 min | Low | An instant browser-based TiDB experience |

## Path 1: Try TiDB locally

**Best for:** first-time users, developers, and feature exploration

**Environment:** macOS or Linux

**What you will do:**

- install TiUP
- start a local TiDB cluster with TiUP Playground
- connect to TiDB
- access TiDB Dashboard and Grafana

**Expected result:** a local TiDB cluster that you can use to test SQL, inspect components, and explore TiDB endpoints.

### Deploy a local test cluster

This section describes how to quickly deploy a local TiDB cluster for testing on a single macOS or Linux server. By deploying such a cluster, you can learn the basic architecture of the TiDB database and the operation of its components, such as TiDB, TiKV, PD, and the monitoring components.

> **Note:**
>
> The deployment method provided in this guide is **ONLY FOR** quick start, **NOT FOR** production or comprehensive functionality and stability testing.
>
> - To deploy a self-hosted production cluster, see the [production installation guide](/production-deployment-using-tiup.md).
> - To deploy TiDB on Kubernetes, see [Get Started with TiDB on Kubernetes](https://docs.pingcap.com/tidb-in-kubernetes/stable/get-started).
> - To manage TiDB in the cloud, see [TiDB Cloud Quick Start](https://docs.pingcap.com/tidbcloud/tidb-cloud-quickstart).

## Deploy a local test cluster

This section describes how to quickly deploy a local TiDB cluster for testing on a single macOS or Linux server. By deploying such a cluster, you can learn the basic architecture of the TiDB database and the operation of its components, such as TiDB, TiKV, PD, and the monitoring components.

<SimpleTab>
<div label="macOS">

</div>
</SimpleTab>

## Simulate production deployment on a single machine
## Path 2: Simulate production deployment

**Best for:** operators, DBAs, and users who want a more realistic deployment workflow

**Environment:** Linux only

**What you will do:**

- prepare a Linux server
- define the smallest TiDB cluster topology
- deploy a full cluster using TiUP
- validate cluster access and endpoints

**Expected result:** a minimal TiDB cluster with a production-style topology on a single machine, ready for deeper evaluation.

### Simulate production deployment on a single machine

This section describes how to set up the smallest TiDB cluster with a full topology, and simulate production deployment steps on a single Linux server.

```shell
tiup clean --all
```

## What's next

<DocHomeCardContainer>

<DocHomeCard href="/basic-sql-operations.md" label="Explore basic SQL operations" icon="oss-developer-blue">

Learn the SQL basics you can try immediately after your cluster is up.

</DocHomeCard>

<DocHomeCard href="/migration-overview.md" label="Migrate data to TiDB" icon="oss-mysql-blue">

Move from evaluation to migration planning with the TiDB migration guides.

</DocHomeCard>

<DocHomeCard href="/tiup/tiup-overview.md" label="Learn TiUP cluster management" icon="oss-product-blue">

Understand how to use TiUP to manage, inspect, and operate TiDB clusters.

</DocHomeCard>

<DocHomeCard href="/production-deployment-using-tiup.md" label="Deploy TiDB for production" icon="oss-deploy-blue">

Continue with the recommended self-hosted production installation workflow.

</DocHomeCard>

<DocHomeCard href="https://docs.pingcap.com/developer/" label="Developer guide overview" icon="oss-developer-blue">

Start building applications on TiDB with language guides and sample apps.

</DocHomeCard>

<DocHomeCard href="/tiflash/tiflash-overview.md" label="Explore TiFlash and HTAP" icon="global-tidb-education">

Learn how to use TiFlash for analytical workloads and HTAP scenarios.

</DocHomeCard>

</DocHomeCardContainer>
