---
id: usage-metrics
title: "Usage metrics"
description: "Learn about the three main usage metrics that impact Camunda Platform 8 pricing."
---

There are three main usage metrics that have an impact on Camunda Platform 8 pricing. It is important to understand these definitions, their impact on billing, and how to retrieve them.

## Definition of metrics

### Root process instance

The number of **root process instance** executions started. This is also known as process instances (PI). A **root process instance** has no parent process instance, i.e. it is a top-level execution.

### Decision instance

The number of evaluated **decision instances** (DI). A **decision instance** is a [DMN decision table](https://docs.camunda.io/docs/8.1/components/modeler/dmn/decision-table/) or a [DMN literal expression](https://docs.camunda.io/docs/8.1/components/modeler/dmn/decision-literal-expression/). In a Decision Requirements Diagram (DRD) each evaluated decision table or expression is counted separately.

### Task user

The number of **task users** (TU) that have served as assignees.

## Retrieve metrics in SaaS

On Camunda Platform 8 SaaS an **Owner** or **Admin** of an organization can retrieve the information from the **Billing** page.

You can access the **Billing** page by selecting **Organization Management** in the Camunda Platform Console navigation bar.

<!-- Billing Page and link to existing guide from Console -->

## Retrieve metrics on Self-Managed

:::caution Important note for Enterprise users

Some Enterprise agreements require the following indices from Elasticsearch for at least 18 months:

For Operate and Tasklist, the metrics are stored in the `operate-metric-1.0.0_` and `tasklist-metric-1.0.0_` indices respectively.
:::

On Camunda Platform 8 Self-Managed, you can get the usage metrics in Operate and Tasklist.

For **root process instances** and **decision instances**, follow the steps provided in the [Operate guide](/self-managed/operate-deployment/usage-metrics.md).

For **task users**, follow the steps provided in the [Tasklist guide](/self-managed/tasklist-deployment/usage-metrics.md).

:::note
If you are not running Tasklist or Operate, there is currently no way to retrieve usage metrics until future releases. Regardless, the metrics still need to be factored into any enterprise agreement and count towards any task user pricing.
:::
