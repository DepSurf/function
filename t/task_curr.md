# Function: <code>task_curr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4987)
Location: kernel/sched/core.c:1000
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:task_function_call
```
**Symbols:**

```
ffffffff810aad90-ffffffff810aadba: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a80a7)
Location: kernel/sched/core.c:918
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
**Symbols:**

```
ffffffff810ad9d0-ffffffff810ad9fa: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae043)
Location: kernel/sched/core.c:925
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810b3ad0-ffffffff810b3af6: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaaf3)
Location: kernel/sched/core.c:846
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810afa30-ffffffff810afa56: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b17f7)
Location: kernel/sched/core.c:856
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810b6e00-ffffffff810b6e26: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b87a7)
Location: kernel/sched/core.c:834
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810be960-ffffffff810be986: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c18c7)
Location: kernel/sched/core.c:829
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810c7c00-ffffffff810c7c26: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c79c5)
Location: kernel/sched/core.c:1272
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810cef70-ffffffff810cef91: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0aa5)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810d8d30-ffffffff810d8d51: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da8c5)
Location: kernel/sched/core.c:1468
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810e2410-ffffffff810e2431: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b95)
Location: kernel/sched/core.c:1679
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810df7f0-ffffffff810df811: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8875)
Location: kernel/sched/core.c:1687
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810e15e0-ffffffff810e1601: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ec11e)
Location: kernel/sched/core.c:2065
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810f76f0-ffffffff810f773e: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811086c5)
Location: kernel/sched/core.c:2161
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:check_slow_task
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff811138f0-ffffffff81113946: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112d665)
Location: kernel/sched/core.c:2149
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:check_slow_task
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/freezer.c:__set_task_frozen
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8113aaa0-ffffffff8113aaf6: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81141e35)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:check_slow_task
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/freezer.c:__set_task_frozen
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81149e00-ffffffff81149e56: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114df75)
Location: kernel/sched/core.c:2214
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/update.c:trc_check_slow_task
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/tree.c:check_slow_task
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/freezer.c:__set_task_frozen
  - kernel/debug/kdb/kdb_main.c:kdb_pid
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81155900-ffffffff81155956: task_curr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010134a94)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffff800010138f90-ffff800010138fbc: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382310)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c038830c-c038834c: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017d460)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
c000000000185610-c00000000018564c: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e587e)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffe0000e8d24-ffffffe0000e8d5c: task_curr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cae25)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810d3200-ffffffff810d3221: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9625)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810c1830-ffffffff810c1851: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca345)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810d08e0-ffffffff810d0901: task_curr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int task_curr(const struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3e20)
Location: kernel/sched/core.c:1392
Inline: True
Inline callers:
  - kernel/sched/core.c:kick_process
Direct callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/rcu/tree.c:rcu_request_urgent_qs_task
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/events/core.c:perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff810da980-ffffffff810da9a1: task_curr (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
