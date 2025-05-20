# Function: <code>atomic_fetch_andnot</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0bd4)
Location: include/linux/atomic.h:553
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1726)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebdc6)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
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
In kernel/sched/core.c (ffffffff810dd8ce)
Location: include/asm-generic/atomic-instrumented.h:476
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/irq_work.c (ffffffff811f74f0)
Location: include/asm-generic/atomic-instrumented.h:476
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da1de)
Location: include/asm-generic/atomic-instrumented.h:476
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
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
In kernel/sched/core.c (ffffffff810dbe51)
Location: include/asm-generic/atomic-instrumented.h:476
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810f6a5a)
Location: include/asm-generic/atomic-instrumented.h:476
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
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
In kernel/sched/core.c (ffffffff810f01ad)
Location: include/linux/atomic/atomic-instrumented.h:347
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811109de)
Location: include/linux/atomic/atomic-instrumented.h:347
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
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
In kernel/sched/core.c (ffffffff8110d76d)
Location: include/linux/atomic/atomic-instrumented.h:366
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8112cbb2)
Location: include/linux/atomic/atomic-instrumented.h:366
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
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
In kernel/sched/core.c (ffffffff81133f0d)
Location: include/linux/atomic/atomic-instrumented.h:366
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811568b2)
Location: include/linux/atomic/atomic-instrumented.h:366
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
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
In kernel/sched/core.c (ffffffff81142c09)
Location: include/linux/atomic/atomic-instrumented.h:858
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8116692c)
Location: include/linux/atomic/atomic-instrumented.h:858
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
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
In kernel/sched/core.c (ffffffff8114dbc9)
Location: include/linux/atomic/atomic-instrumented.h:858
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8117366c)
Location: include/linux/atomic/atomic-instrumented.h:858
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014c0f8)
Location: include/asm-generic/atomic-instrumented.h:475
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0399d6c)
Location: include/linux/atomic-fallback.h:725
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019e9b0)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f5744)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e5f26)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d50c6)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e22f6)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ede96)
Location: include/linux/atomic-fallback.h:666
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
</ul>

## Differences
