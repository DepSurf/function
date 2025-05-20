# Function: <code>nsec_high</code>

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
In kernel/sched/debug.c (ffffffff810c54ff)
Location: kernel/sched/debug.c:39
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
In kernel/sched/debug.c (ffffffff810cca73)
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
In kernel/sched/debug.c (ffffffff810d2a8f)
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
In kernel/sched/debug.c (ffffffff810d1bdf)
Location: kernel/sched/debug.c:41
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
In kernel/sched/debug.c (ffffffff810d9780)
Location: kernel/sched/debug.c:41
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
In kernel/sched/debug.c (ffffffff810e07a6)
Location: kernel/sched/debug.c:31
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
In kernel/sched/debug.c (ffffffff810eaf5c)
Location: kernel/sched/debug.c:31
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
In kernel/sched/debug.c (ffffffff810f1d81)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff810fda41)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff8110813a)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff8110694a)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff81108993)
Location: kernel/sched/debug.c:26
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
In kernel/sched/debug.c (ffffffff81126b03)
Location: kernel/sched/debug.c:26
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
In kernel/sched/build_utility.c (ffffffff8114722a)
Location: kernel/sched/debug.c:25
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
In kernel/sched/build_utility.c (ffffffff81174c4b)
Location: kernel/sched/debug.c:25
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
In kernel/sched/build_utility.c (ffffffff81185855)
Location: kernel/sched/debug.c:25
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
In kernel/sched/build_utility.c (ffffffff81193f99)
Location: kernel/sched/debug.c:25
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
In kernel/sched/debug.c (ffff80001016322c)
Location: kernel/sched/debug.c:28
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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long long int nsec_high(long long unsigned int nsec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ac758)
Location: kernel/sched/debug.c:28
Inline: True
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
c03ac758-c03ac810: nsec_high (STB_LOCAL)
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
In kernel/sched/debug.c (c0000000001b9a80)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffe000106d58)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff810f6d61)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff810e6f31)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff810f3f71)
Location: kernel/sched/debug.c:28
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
In kernel/sched/debug.c (ffffffff810fef64)
Location: kernel/sched/debug.c:28
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
