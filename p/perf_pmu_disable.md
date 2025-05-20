# Function: <code>perf_pmu_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117a8b0)
Location: kernel/events/core.c:828
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
```
**Symbols:**

```
ffffffff8117a8b0-ffffffff8117a8b9: perf_pmu_disable.part.88 (STB_LOCAL)
ffffffff8117f4f0-ffffffff8117f513: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118b65f)
Location: kernel/events/core.c:1073
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8118b5d0-ffffffff8118b5d9: perf_pmu_disable.part.91 (STB_LOCAL)
ffffffff81191280-ffffffff811912a3: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8119a4ff)
Location: kernel/events/core.c:1081
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:group_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:group_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8119a320-ffffffff8119a329: perf_pmu_disable.part.92 (STB_LOCAL)
ffffffff811a0960-ffffffff811a0983: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a052f)
Location: kernel/events/core.c:1073
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:group_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
```
**Symbols:**

```
ffffffff811a8340-ffffffff811a8362: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3e9f)
Location: kernel/events/core.c:1112
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
```
**Symbols:**

```
ffffffff811bbab0-ffffffff811bbad6: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d554f)
Location: kernel/events/core.c:1135
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811d54c0-ffffffff811d54cf: perf_pmu_disable.part.103 (STB_LOCAL)
ffffffff811dbc40-ffffffff811dbc62: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e5bef)
Location: kernel/events/core.c:1135
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811e5b60-ffffffff811e5b6f: perf_pmu_disable.part.103 (STB_LOCAL)
ffffffff811ec000-ffffffff811ec022: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fd3c6)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811fd330-ffffffff811fd33f: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff81203990-ffffffff812039b3: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120a676)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8120a5e0-ffffffff8120a5ef: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff81210580-ffffffff812105a3: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812357cd)
Location: kernel/events/core.c:1198
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8123c780-ffffffff8123c7a7: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f99d)
Location: kernel/events/core.c:1202
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff81246a20-ffffffff81246a47: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243b3d)
Location: kernel/events/core.c:1200
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8124a790-ffffffff8124a7b7: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127dbdd)
Location: kernel/events/core.c:1231
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff812840c0-ffffffff812840e7: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d2920)
Location: kernel/events/core.c:1140
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff812d8420-ffffffff812d8464: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b1d0)
Location: kernel/events/core.c:1137
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_ctx_disable
  - kernel/events/core.c:perf_ctx_disable
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff81340920-ffffffff81340964: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c250)
Location: kernel/events/core.c:1137
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_ctx_disable
  - kernel/events/core.c:perf_ctx_disable
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff813718c0-ffffffff81371904: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395410)
Location: kernel/events/core.c:1148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:__pmu_ctx_sched_out
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:event_sched_out
  - kernel/events/core.c:perf_ctx_disable
  - kernel/events/core.c:perf_ctx_disable
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8139abc0-ffffffff8139ac04: perf_pmu_disable (STB_GLOBAL)
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
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102991d8)
Location: kernel/events/core.c:1136
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffff8000102991d8-ffff800010299208: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8480)
Location: kernel/events/core.c:1136
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c04c8480-c04c84b4: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003484f0)
Location: kernel/events/core.c:1136
Inline: True
Direct callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_start_txn
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
  - arch/powerpc/perf/core-book3s.c:power_pmu_add
  - arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_start_txn
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c0000000003484f0-c000000000348544: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cac66)
Location: kernel/events/core.c:1136
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_start_txn
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffe0001cac66-ffffffe0001cac9e: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81202c96)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81202c00-ffffffff81202c0f: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff81208bd0-ffffffff81208bf3: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f59e6)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811f5950-ffffffff811f595f: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff811fb960-ffffffff811fb983: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81200a66)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff812009d0-ffffffff812009df: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff81206970-ffffffff81206993: perf_pmu_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_disable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120fc16)
Location: kernel/events/core.c:1136
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8120fa60-ffffffff8120fa6f: perf_pmu_disable.part.0 (STB_LOCAL)
ffffffff812156e0-ffffffff81215703: perf_pmu_disable (STB_GLOBAL)
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
