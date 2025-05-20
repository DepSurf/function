# Function: <code>task_numa_group_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba360)
Location: kernel/sched/fair.c:905
Inline: False
Direct callers:
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810ba360-ffffffff810ba37e: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd7c0)
Location: kernel/sched/fair.c:1040
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810bd7c0-ffffffff810bd7de: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2d20)
Location: kernel/sched/fair.c:1164
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810c2d20-ffffffff810c2d3e: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd9f0)
Location: kernel/sched/fair.c:1161
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810bd9f0-ffffffff810bda0c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c56e0)
Location: kernel/sched/fair.c:1178
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810c56e0-ffffffff810c56fc: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cd090)
Location: kernel/sched/fair.c:1206
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810cd090-ffffffff810cd0ac: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5a50)
Location: kernel/sched/fair.c:1202
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - fs/proc/array.c:proc_pid_status
```
**Symbols:**

```
ffffffff810d5a50-ffffffff810d5a6c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de4f0)
Location: kernel/sched/fair.c:1253
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810de4f0-ffffffff810de50c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8a40)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810e8a40-ffffffff810e8a5c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3210)
Location: kernel/sched/fair.c:1222
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810f3210-ffffffff810f322c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f1440)
Location: kernel/sched/fair.c:1229
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810f1440-ffffffff810f146c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3730)
Location: kernel/sched/fair.c:1226
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810f3730-ffffffff810f375c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110cfa0)
Location: kernel/sched/fair.c:1215
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff8110cfa0-ffffffff8110cfcc: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81128b30)
Location: kernel/sched/fair.c:1217
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff81128b30-ffffffff81128b66: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152220)
Location: kernel/sched/fair.c:1256
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff81152220-ffffffff81152256: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81161b10)
Location: kernel/sched/fair.c:1273
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff81161b10-ffffffff81161b46: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116e5e0)
Location: kernel/sched/fair.c:1514
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff8116e5e0-ffffffff8116e616: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101488e0)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffff8000101488e0-ffff800010148920: task_numa_group_id (STB_GLOBAL)
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
In kernel/sched/core.c (0)
Location: include/linux/sched/numa_balancing.h:30
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched/numa_balancing.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019a2e0)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
c00000000019a2e0-c00000000019a300: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/sched/numa_balancing.h:30
Inline: True
```
```
In fs/proc/array.c (0)
Location: include/linux/sched/numa_balancing.h:30
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2bf0)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810e2bf0-ffffffff810e2c0c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1d00)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810d1d00-ffffffff810d1d1c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810def70)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810def70-ffffffff810def8c: task_numa_group_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pid_t task_numa_group_id(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eaa90)
Location: kernel/sched/fair.c:1211
Inline: False
Direct callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - fs/proc/array.c:task_state
```
**Symbols:**

```
ffffffff810eaa90-ffffffff810eaac4: task_numa_group_id (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
