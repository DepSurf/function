# Function: <code>__uclamp_update_util_min_rt_default</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2262)
Location: kernel/sched/core.c:997
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:uclamp_sync_util_min_rt_default
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
In kernel/sched/core.c (ffffffff810e4072)
Location: kernel/sched/core.c:1007
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810fad82)
Location: kernel/sched/core.c:1361
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff811171a0)
Location: kernel/sched/core.c:1431
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff8113e690)
Location: kernel/sched/core.c:1419
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff8114b190)
Location: kernel/sched/core.c:1441
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff81156dad)
Location: kernel/sched/core.c:1486
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
