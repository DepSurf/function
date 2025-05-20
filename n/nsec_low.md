# Function: <code>nsec_low</code>

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
In kernel/sched/debug.c (ffffffff810c54e3)
Location: kernel/sched/debug.c:51
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810cca57)
Location: kernel/sched/debug.c:52
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810d2a73)
Location: kernel/sched/debug.c:52
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810d1bbc)
Location: kernel/sched/debug.c:53
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810d975d)
Location: kernel/sched/debug.c:53
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810e0772)
Location: kernel/sched/debug.c:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810eaf28)
Location: kernel/sched/debug.c:43
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810f1d4d)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810fda0d)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff81108109)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff81106919)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff8110895f)
Location: kernel/sched/debug.c:38
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff81126acf)
Location: kernel/sched/debug.c:38
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/build_utility.c (ffffffff811471f9)
Location: kernel/sched/debug.c:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
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
In kernel/sched/build_utility.c (ffffffff81174c1a)
Location: kernel/sched/debug.c:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
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
In kernel/sched/build_utility.c (ffffffff81185827)
Location: kernel/sched/debug.c:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
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
In kernel/sched/build_utility.c (ffffffff81193f6b)
Location: kernel/sched/debug.c:37
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:proc_sched_show_task
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:sched_debug_header
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_rt_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
  - kernel/sched/build_utility.c:print_cfs_rq
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
In kernel/sched/debug.c (ffff800010163248)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int nsec_low(long long unsigned int nsec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ac6e0)
Location: kernel/sched/debug.c:40
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
```
**Symbols:**

```
c03ac6e0-c03ac758: nsec_low (STB_LOCAL)
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
In kernel/sched/debug.c (c0000000001b9aa4)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
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
In kernel/sched/debug.c (ffffffe000106d60)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
  - kernel/sched/debug.c:print_cfs_group_stats
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
In kernel/sched/debug.c (ffffffff810f6d2d)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810e6efd)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810f3f3d)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
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
In kernel/sched/debug.c (ffffffff810fef30)
Location: kernel/sched/debug.c:40
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:sched_debug_header
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_rt_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
  - kernel/sched/debug.c:print_cfs_rq
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
