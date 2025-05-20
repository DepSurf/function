# Function: <code>dl_bw_of</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dl_bw *dl_bw_of(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9b95)
Location: kernel/sched/core.c:2283
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
Direct callers:
  - kernel/sched/deadline.c:task_dead_dl
  - kernel/sched/deadline.c:set_cpus_allowed_dl
```
**Symbols:**

```
ffffffff810acce0-ffffffff810acd06: dl_bw_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dl_bw *dl_bw_of(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b345d)
Location: kernel/sched/core.c:2462
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:__sched_setscheduler
Direct callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:task_dead_dl
```
**Symbols:**

```
ffffffff810af720-ffffffff810af746: dl_bw_of (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dl_bw *dl_bw_of(int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9aad)
Location: kernel/sched/core.c:2472
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_rt_handler
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:task_can_attach
  - kernel/sched/core.c:cpuset_cpumask_can_shrink
  - kernel/sched/core.c:__sched_setscheduler
Direct callers:
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:task_dead_dl
```
**Symbols:**

```
ffffffff810b5860-ffffffff810b5884: dl_bw_of (STB_GLOBAL)
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
In kernel/sched/deadline.c (ffffffff810c9336)
Location: kernel/sched/deadline.c:48
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810d0a26)
Location: kernel/sched/deadline.c:49
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810d8f46)
Location: kernel/sched/deadline.c:46
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810e2a46)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810e9552)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810f5032)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810fe752)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810fd0a6)
Location: kernel/sched/deadline.c:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
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
In kernel/sched/deadline.c (ffffffff810ff446)
Location: kernel/sched/deadline.c:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
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
In kernel/sched/deadline.c (ffffffff8111b446)
Location: kernel/sched/deadline.c:69
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
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
In kernel/sched/build_policy.c (ffffffff8113b0e1)
Location: kernel/sched/deadline.c:99
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
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
In kernel/sched/build_policy.c (ffffffff81165a81)
Location: kernel/sched/deadline.c:101
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_cpu_busy
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
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
In kernel/sched/build_policy.c (ffffffff8116d0a4)
Location: kernel/sched/deadline.c:103
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
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
In kernel/sched/build_policy.c (ffffffff81179ae4)
Location: kernel/sched/deadline.c:116
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_bw_manage
  - kernel/sched/build_policy.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_do_global
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
In kernel/sched/deadline.c (ffff8000101578c0)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (c03a562c)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (c0000000001ac484)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffe0000fe5e4)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810ee432)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810de4c2)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810eb562)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
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
In kernel/sched/deadline.c (ffffffff810f65a9)
Location: kernel/sched/deadline.c:47
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_cpu_busy
  - kernel/sched/deadline.c:dl_cpuset_cpumask_can_shrink
  - kernel/sched/deadline.c:dl_task_can_attach
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_do_global
  - kernel/sched/deadline.c:sched_dl_global_validate
  - kernel/sched/deadline.c:set_cpus_allowed_dl
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
