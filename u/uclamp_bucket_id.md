# Function: <code>uclamp_bucket_id</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ccf07)
Location: kernel/sched/core.c:791
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810d53eb)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810df9b8)
Location: kernel/sched/core.c:823
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810dcca8)
Location: kernel/sched/core.c:929
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:__setscheduler_uclamp
  - kernel/sched/core.c:__setscheduler_uclamp
  - kernel/sched/core.c:__setscheduler_uclamp
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810de86c)
Location: kernel/sched/core.c:939
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffffffff810f36bc)
Location: kernel/sched/core.c:1293
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffffffff8110f717)
Location: kernel/sched/core.c:1363
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffffffff81136587)
Location: kernel/sched/core.c:1351
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffffffff811455c7)
Location: kernel/sched/core.c:1373
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffffffff81150ae7)
Location: kernel/sched/core.c:1418
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
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
In kernel/sched/core.c (ffff800010135ef4)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (c0384a6c)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (c000000000180eb0)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/sched/core.c (ffffffff810cf6eb)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810bdfab)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d724b)
Location: kernel/sched/core.c:803
Inline: True
Inline callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
</details>
</li>
</ul>

## Differences
