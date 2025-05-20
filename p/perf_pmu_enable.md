# Function: <code>perf_pmu_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117a8f0)
Location: kernel/events/core.c:835
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff8117a8f0-ffffffff8117a8f9: perf_pmu_enable.part.90 (STB_LOCAL)
ffffffff8117f520-ffffffff8117f543: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118b6b3)
Location: kernel/events/core.c:1080
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff8118b610-ffffffff8118b619: perf_pmu_enable.part.93 (STB_LOCAL)
ffffffff811912b0-ffffffff811912d3: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8119a553)
Location: kernel/events/core.c:1088
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff8119a360-ffffffff8119a369: perf_pmu_enable.part.94 (STB_LOCAL)
ffffffff811a0990-ffffffff811a09b3: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0589)
Location: kernel/events/core.c:1080
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
```
**Symbols:**

```
ffffffff811a8370-ffffffff811a838c: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3f08)
Location: kernel/events/core.c:1119
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
```
**Symbols:**

```
ffffffff811bbae0-ffffffff811bbb00: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d55b5)
Location: kernel/events/core.c:1142
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff811d5500-ffffffff811d550f: perf_pmu_enable.part.105 (STB_LOCAL)
ffffffff811dbc70-ffffffff811dbc8c: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e5c55)
Location: kernel/events/core.c:1142
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff811e5ba0-ffffffff811e5baf: perf_pmu_enable.part.105 (STB_LOCAL)
ffffffff811ec030-ffffffff811ec04c: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fd42f)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff811fd370-ffffffff811fd37f: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff812039c0-ffffffff812039dd: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120a6df)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff8120a620-ffffffff8120a62f: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff812105b0-ffffffff812105cd: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81235858)
Location: kernel/events/core.c:1205
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8123c7b0-ffffffff8123c7d1: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123fa28)
Location: kernel/events/core.c:1209
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff81246a50-ffffffff81246a71: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243bc8)
Location: kernel/events/core.c:1207
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8124a7c0-ffffffff8124a7e1: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127e498)
Location: kernel/events/core.c:1238
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff812840f0-ffffffff81284111: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d29e9)
Location: kernel/events/core.c:1147
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff812d8470-ffffffff812d84ae: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133b2b9)
Location: kernel/events/core.c:1144
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - kernel/events/core.c:perf_ctx_enable
  - kernel/events/core.c:perf_ctx_enable
Direct callers:
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff81340980-ffffffff813409be: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c579)
Location: kernel/events/core.c:1144
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - kernel/events/core.c:perf_ctx_enable
  - kernel/events/core.c:perf_ctx_enable
Direct callers:
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff81371920-ffffffff8137195e: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813956c9)
Location: kernel/events/core.c:1155
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
  - kernel/events/core.c:perf_ctx_enable
  - kernel/events/core.c:perf_ctx_enable
Direct callers:
  - arch/x86/events/core.c:x86_pmu_commit_txn
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/ds.c:intel_pmu_auto_reload_read
```
**Symbols:**

```
ffffffff8139ac20-ffffffff8139ac5e: perf_pmu_enable (STB_GLOBAL)
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
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010299238)
Location: kernel/events/core.c:1143
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
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
ffff800010299238-ffff800010299268: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c84e0)
Location: kernel/events/core.c:1143
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:__perf_event_period
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c04c84e0-c04c8514: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000348580)
Location: kernel/events/core.c:1143
Inline: True
Direct callers:
  - arch/powerpc/perf/core-book3s.c:power_pmu_commit_txn
  - arch/powerpc/perf/core-book3s.c:power_pmu_cancel_txn
  - arch/powerpc/perf/core-book3s.c:power_pmu_cancel_txn
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
  - arch/powerpc/perf/core-book3s.c:power_pmu_add
  - arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_commit_txn
  - arch/powerpc/perf/imc-pmu.c:thread_imc_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c000000000348580-c0000000003485d4: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cacdc)
Location: kernel/events/core.c:1143
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_cancel_txn
  - kernel/events/core.c:perf_pmu_commit_txn
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:ctx_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:event_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffe0001cacdc-ffffffe0001cad14: perf_pmu_enable (STB_GLOBAL)
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
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81202cff)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff81202c40-ffffffff81202c4f: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff81208c00-ffffffff81208c1d: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811f5a4f)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff811f5990-ffffffff811f599f: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff811fb990-ffffffff811fb9ad: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81200acf)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff81200a10-ffffffff81200a1f: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff812069a0-ffffffff812069bd: perf_pmu_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void perf_pmu_enable(struct pmu *pmu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120fc7f)
Location: kernel/events/core.c:1143
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
  - arch/x86/events/core.c:x86_pmu_commit_txn
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
ffffffff8120faa0-ffffffff8120faaf: perf_pmu_enable.part.0 (STB_LOCAL)
ffffffff81215710-ffffffff8121572d: perf_pmu_enable (STB_GLOBAL)
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
