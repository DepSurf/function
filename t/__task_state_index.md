# Function: <code>__task_state_index</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81109d97)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/build_utility.c (ffffffff8113b523)
Location: include/linux/sched.h:1631
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd858)
Location: include/linux/sched.h:1631
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122edb2)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff814a5e5c)
Location: include/linux/sched.h:1631
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff811314d4)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/build_utility.c (ffffffff8116aace)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81245028)
Location: include/linux/sched.h:1653
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127add4)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff8153b49c)
Location: include/linux/sched.h:1653
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff8113f464)
Location: include/linux/sched.h:1662
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/build_utility.c (ffffffff8117b1de)
Location: include/linux/sched.h:1662
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c0b8)
Location: include/linux/sched.h:1662
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812928f4)
Location: include/linux/sched.h:1662
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff815737cc)
Location: include/linux/sched.h:1662
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff8114c3ac)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/build_utility.c (ffffffff81188b90)
Location: include/linux/sched.h:1570
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811d3dad)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81275ff2)
Location: include/linux/sched.h:1570
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adfd3)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff815ac1a9)
Location: include/linux/sched.h:1570
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
