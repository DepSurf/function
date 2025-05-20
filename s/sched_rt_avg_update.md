# Function: <code>sched_rt_avg_update</code>

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
In kernel/sched/rt.c (ffffffff810bfb2a)
Location: kernel/sched/sched.h:1418
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c223a)
Location: kernel/sched/sched.h:1418
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810c3456)
Location: kernel/sched/sched.h:1455
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c5c10)
Location: kernel/sched/sched.h:1455
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810c94c6)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cbbd0)
Location: kernel/sched/sched.h:1494
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810c4765)
Location: kernel/sched/sched.h:1675
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810c7ea6)
Location: kernel/sched/sched.h:1675
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810cbe58)
Location: kernel/sched/sched.h:1714
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810cf60f)
Location: kernel/sched/sched.h:1714
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
In kernel/sched/rt.c (ffffffff810d3560)
Location: kernel/sched/sched.h:1751
Inline: True
Inline callers:
  - kernel/sched/rt.c:update_curr_rt
```
```
In kernel/sched/deadline.c (ffffffff810d7161)
Location: kernel/sched/sched.h:1751
Inline: True
Inline callers:
  - kernel/sched/deadline.c:update_curr_dl
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
