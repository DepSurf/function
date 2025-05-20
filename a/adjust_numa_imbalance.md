# Function: <code>adjust_numa_imbalance</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4dbd)
Location: kernel/sched/fair.c:8946
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810e6733)
Location: kernel/sched/fair.c:9044
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8701)
Location: kernel/sched/fair.c:9098
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ffdd1)
Location: kernel/sched/fair.c:9333
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111afe2)
Location: kernel/sched/fair.c:9407
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81142a6c)
Location: kernel/sched/fair.c:1071
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152a4c)
Location: kernel/sched/fair.c:1088
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115f398)
Location: kernel/sched/fair.c:1329
Inline: True
Inline callers:
  - kernel/sched/fair.c:calculate_imbalance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
