# Function: <code>dl_bw_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9bf4)
Location: kernel/sched/core.c:2290
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:task_can_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2a61)
Location: kernel/sched/core.c:2469
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9079)
Location: kernel/sched/core.c:2479
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:__sched_setscheduler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c9360)
Location: kernel/sched/deadline.c:55
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d0a50)
Location: kernel/sched/deadline.c:56
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d8f71)
Location: kernel/sched/deadline.c:53
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e2a71)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810e9581)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f5061)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fe780)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810fd17b)
Location: kernel/sched/deadline.c:76
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810ff52a)
Location: kernel/sched/deadline.c:76
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff8111b563)
Location: kernel/sched/deadline.c:76
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff8113b33c)
Location: kernel/sched/deadline.c:106
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff81165cf4)
Location: kernel/sched/deadline.c:108
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff8116d3e1)
Location: kernel/sched/deadline.c:110
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/build_policy.c (ffffffff81179b31)
Location: kernel/sched/deadline.c:123
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:set_cpus_allowed_dl
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
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
In kernel/sched/deadline.c (ffff800010157914)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c03a5684)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (c0000000001ac4c8)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffe0000fe604)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810ee461)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810de4f1)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810eb591)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
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
In kernel/sched/deadline.c (ffffffff810f65d8)
Location: kernel/sched/deadline.c:54
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
</ul>

## Differences
