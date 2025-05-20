# Function: <code>arch_atomic_fetch_andnot</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
Location: include/linux/atomic-arch-fallback.h:668
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/irq_work.c (ffffffff811f74f0)
Location: include/linux/atomic-arch-fallback.h:668
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
Location: include/linux/atomic-arch-fallback.h:738
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
Location: include/linux/atomic-arch-fallback.h:738
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff810f6a5a)
Location: include/linux/atomic-arch-fallback.h:738
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
Location: include/linux/atomic/atomic-arch-fallback.h:738
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811109de)
Location: include/linux/atomic/atomic-arch-fallback.h:738
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
Location: include/linux/atomic/atomic-arch-fallback.h:822
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff8112cbb2)
Location: include/linux/atomic/atomic-arch-fallback.h:822
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
Location: include/linux/atomic/atomic-arch-fallback.h:822
Inline: True
Inline callers:
  - kernel/sched/core.c:nohz_csd_func
```
```
In kernel/sched/fair.c (ffffffff811568b2)
Location: include/linux/atomic/atomic-arch-fallback.h:822
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_run_idle_balance
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
Location: arch/arm64/include/asm/atomic.h:46
Inline: True
Inline callers:
  - kernel/sched/fair.c:run_rebalance_domains
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
