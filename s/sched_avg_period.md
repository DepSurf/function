# Function: <code>sched_avg_period</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa7e5)
Location: kernel/sched/sched.h:1364
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (0)
Location: kernel/sched/sched.h:1364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad425)
Location: kernel/sched/sched.h:1401
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810bfed2)
Location: kernel/sched/sched.h:1401
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3525)
Location: kernel/sched/sched.h:1440
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810c5ed1)
Location: kernel/sched/sched.h:1440
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af42d)
Location: kernel/sched/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810bfa70)
Location: kernel/sched/sched.h:1621
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/core.c (ffffffff810b66fd)
Location: kernel/sched/sched.h:1660
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810c7232)
Location: kernel/sched/sched.h:1660
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
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
In kernel/sched/core.c (ffffffff810be715)
Location: kernel/sched/sched.h:1697
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_avg_update
```
```
In kernel/sched/fair.c (ffffffff810cf173)
Location: kernel/sched/sched.h:1697
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_group_capacity
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
