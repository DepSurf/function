# Function: <code>rseq_set_notify_resume</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819ec5e1)
Location: include/linux/sched.h:1796
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff811ea055)
Location: include/linux/sched.h:1796
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a27863)
Location: include/linux/sched.h:1809
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff811fabc5)
Location: include/linux/sched.h:1809
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a9810b)
Location: include/linux/sched.h:1882
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff812122d0)
Location: include/linux/sched.h:1882
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81acf9e1)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff8121fab0)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dde41)
Location: include/linux/sched.h:1928
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff8124bd9e)
Location: include/linux/sched.h:1928
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff810da3b1)
Location: include/linux/sched.h:1989
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/membarrier.c (ffffffff81108fe1)
Location: include/linux/sched.h:1989
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff81256234)
Location: include/linux/sched.h:1989
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff810dc9d9)
Location: include/linux/sched.h:2066
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/membarrier.c (ffffffff8110b091)
Location: include/linux/sched.h:2066
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff8125a806)
Location: include/linux/sched.h:2066
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff810f1501)
Location: include/linux/sched.h:2185
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/membarrier.c (ffffffff811298f1)
Location: include/linux/sched.h:2185
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff812965f6)
Location: include/linux/sched.h:2185
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff8110d8f1)
Location: include/linux/sched.h:2281
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_utility.c (ffffffff8113eea1)
Location: include/linux/sched.h:2281
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff812ec5ac)
Location: include/linux/sched.h:2281
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff81134611)
Location: include/linux/sched.h:2309
Inline: True
Inline callers:
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_utility.c (ffffffff811692f1)
Location: include/linux/sched.h:2309
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff813568dc)
Location: include/linux/sched.h:2309
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff8115249b)
Location: include/linux/sched.h:2326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_utility.c (ffffffff811799f1)
Location: include/linux/sched.h:2326
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff81388077)
Location: include/linux/sched.h:2326
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
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
In kernel/sched/core.c (ffffffff8115e360)
Location: include/linux/rseq.h:26
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:prepare_task_switch
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:sched_cgroup_fork
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/sched/build_utility.c (ffffffff81187421)
Location: include/linux/rseq.h:26
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_rseq
```
```
In kernel/rseq.c (ffffffff813b1ad7)
Location: include/linux/rseq.h:26
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da161c)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffff8000102ac6a0)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__arm64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e99748)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (c04d9ccc)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee26a4)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (c000000000360630)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__se_sys_rseq
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6e851)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff81218100)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2ac4a)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff8120b310)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adac61)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff81215ea0)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae7113)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:set_task_cpu
```
```
In kernel/rseq.c (ffffffff812252a0)
Location: include/linux/sched.h:1878
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
```
</details>
</li>
</ul>

## Differences
