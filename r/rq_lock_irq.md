# Function: <code>rq_lock_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af73c)
Location: kernel/sched/sched.h:1718
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810c18f5)
Location: kernel/sched/sched.h:1718
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6a12)
Location: kernel/sched/sched.h:1757
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810c9055)
Location: kernel/sched/sched.h:1757
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc60f)
Location: kernel/sched/sched.h:1801
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810c7daf)
Location: kernel/sched/sched.h:1801
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4def)
Location: kernel/sched/sched.h:1138
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810d28ff)
Location: kernel/sched/sched.h:1138
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce4a3)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810da56f)
Location: kernel/sched/sched.h:1196
Inline: True
Inline callers:
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d80a3)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810ecb0d)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df3ef)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810f69a9)
Location: kernel/sched/sched.h:1252
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc088)
Location: kernel/sched/sched.h:1310
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810f4b39)
Location: kernel/sched/sched.h:1310
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de0a8)
Location: kernel/sched/sched.h:1323
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810f6c29)
Location: kernel/sched/sched.h:1323
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2d6f)
Location: kernel/sched/sched.h:1610
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff81110e66)
Location: kernel/sched/sched.h:1610
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110eb2a)
Location: kernel/sched/sched.h:1591
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff8112d085)
Location: kernel/sched/sched.h:1591
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811358f0)
Location: kernel/sched/sched.h:1637
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff81156df1)
Location: kernel/sched/sched.h:1637
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_utility.c (ffffffff8117b020)
Location: kernel/sched/sched.h:1637
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144a57)
Location: kernel/sched/sched.h:1664
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff81166eb1)
Location: kernel/sched/sched.h:1664
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_utility.c (ffffffff8118bb5e)
Location: kernel/sched/sched.h:1664
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114ffa5)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff81173c31)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
```
In kernel/sched/build_utility.c (ffffffff8119a4be)
Location: kernel/sched/sched.h:1688
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_cgroup_restart
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101387ac)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffff80001014d040)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0387548)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (c039ad3c)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000184510)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (c00000000019fe38)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e86d0)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffe0000f6428)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2573)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810e6c6d)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0ba7)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/fair.c (ffffffff810d5e0d)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0323)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810e303d)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9c78)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
```
```
In kernel/sched/fair.c (ffffffff810eec1d)
Location: kernel/sched/sched.h:1204
Inline: True
Inline callers:
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:active_load_balance_cpu_stop
```
</details>
</li>
</ul>

## Differences
