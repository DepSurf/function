# Function: <code>rseq_preempt</code>

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
In kernel/sched/core.c (ffffffff819ec5d7)
Location: include/linux/sched.h:1821
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a27859)
Location: include/linux/sched.h:1834
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a98102)
Location: include/linux/sched.h:1907
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81acf9d8)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dde38)
Location: include/linux/sched.h:1953
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
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
In kernel/sched/core.c (ffffffff810da3a8)
Location: include/linux/sched.h:2014
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/membarrier.c (ffffffff81108fd8)
Location: include/linux/sched.h:2014
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff810dc9cd)
Location: include/linux/sched.h:2091
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/membarrier.c (ffffffff8110b088)
Location: include/linux/sched.h:2091
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff810f14f5)
Location: include/linux/sched.h:2210
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/membarrier.c (ffffffff811298e8)
Location: include/linux/sched.h:2210
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff8110d8e5)
Location: include/linux/sched.h:2306
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/build_utility.c (ffffffff8113ee98)
Location: include/linux/sched.h:2306
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff81134605)
Location: include/linux/sched.h:2334
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/build_utility.c (ffffffff811692e8)
Location: include/linux/sched.h:2334
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff81143802)
Location: include/linux/sched.h:2351
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/build_utility.c (ffffffff811799e8)
Location: include/linux/sched.h:2351
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
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
In kernel/sched/core.c (ffffffff8114ed22)
Location: include/linux/rseq.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
```
```
In kernel/sched/build_utility.c (ffffffff81187418)
Location: include/linux/rseq.h:51
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
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
In kernel/sched/core.c (ffff800010da160c)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (c0e99734)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (c000000000ee2690)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (0)
Location: include/linux/sched.h:1953
Inline: True
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
In kernel/sched/core.c (ffffffff81a6e848)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81a2ac41)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81adac58)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
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
In kernel/sched/core.c (ffffffff81ae710a)
Location: include/linux/sched.h:1903
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
</ul>

## Differences
