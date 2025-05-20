# Function: <code>uclamp_se_set</code>

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
In kernel/sched/core.c (ffffffff828c50ff)
Location: kernel/sched/core.c:808
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff810de1a1)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810e6770)
Location: kernel/sched/core.c:840
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:init_uclamp
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
In kernel/sched/core.c (ffffffff810e4670)
Location: kernel/sched/core.c:941
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:init_uclamp
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
In kernel/sched/core.c (ffffffff810e6620)
Location: kernel/sched/core.c:951
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff810fdb70)
Location: kernel/sched/core.c:1305
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff8111a5b4)
Location: kernel/sched/core.c:1375
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff81141e44)
Location: kernel/sched/core.c:1363
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff8114db14)
Location: kernel/sched/core.c:1385
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff81159924)
Location: kernel/sched/core.c:1430
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_post_fork
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:uclamp_rq_inc_id
  - kernel/sched/core.c:uclamp_eff_value
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
In kernel/sched/core.c (ffff80001013dc38)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (c038dc08)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (c00000000018cc38)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810d8391)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810c6da1)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
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
In kernel/sched/core.c (ffffffff810dff71)
Location: kernel/sched/core.c:820
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_create_group
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
</details>
</li>
</ul>

## Differences
