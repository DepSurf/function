# Function: <code>task_state_index</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3d64)
Location: include/linux/sched.h:1239
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810d72d5)
Location: include/linux/sched.h:1239
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117cd38)
Location: include/linux/sched.h:1239
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff812f404c)
Location: include/linux/sched.h:1239
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810baf71)
Location: include/linux/sched.h:1331
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810e1b88)
Location: include/linux/sched.h:1331
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118bd9a)
Location: include/linux/sched.h:1331
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81321465)
Location: include/linux/sched.h:1331
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/core.c (ffffffff810c44a1)
Location: include/linux/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810ec2d8)
Location: include/linux/sched.h:1333
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811997b8)
Location: include/linux/sched.h:1333
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81338575)
Location: include/linux/sched.h:1333
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/core.c (ffffffff810ca1fb)
Location: include/linux/sched.h:1405
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810eff81)
Location: include/linux/sched.h:1405
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a73ea)
Location: include/linux/sched.h:1405
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81360c35)
Location: include/linux/sched.h:1405
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810d345b)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810fbddf)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2bda)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81378e95)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810dd152)
Location: include/linux/sched.h:1440
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff8110652c)
Location: include/linux/sched.h:1440
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cac15)
Location: include/linux/sched.h:1440
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In fs/proc/array.c (ffffffff813c1f42)
Location: include/linux/sched.h:1440
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810d99f2)
Location: include/linux/sched.h:1499
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff81104b7c)
Location: include/linux/sched.h:1499
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c82f5)
Location: include/linux/sched.h:1499
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
```
```
In fs/proc/array.c (ffffffff813d4092)
Location: include/linux/sched.h:1499
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810db412)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff81106f12)
Location: include/linux/sched.h:1521
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c9a66)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff813daed2)
Location: include/linux/sched.h:1521
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810ef9b9)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff81124ec9)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9c77)
Location: include/linux/sched.h:1619
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f554d)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff8142c5ad)
Location: include/linux/sched.h:1619
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff8110ba9d)
Location: include/linux/sched.h:1652
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8113b510)
Location: include/linux/sched.h:1652
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd84f)
Location: include/linux/sched.h:1652
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122eda7)
Location: include/linux/sched.h:1652
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff814a5e5c)
Location: include/linux/sched.h:1652
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
In kernel/sched/core.c (ffffffff81131e5e)
Location: include/linux/sched.h:1674
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8116aadc)
Location: include/linux/sched.h:1674
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8124501f)
Location: include/linux/sched.h:1674
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127adc9)
Location: include/linux/sched.h:1674
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff8153b49c)
Location: include/linux/sched.h:1674
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
In kernel/sched/core.c (ffffffff811400d6)
Location: include/linux/sched.h:1683
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117b1ec)
Location: include/linux/sched.h:1683
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c0af)
Location: include/linux/sched.h:1683
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812928e9)
Location: include/linux/sched.h:1683
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff815737cc)
Location: include/linux/sched.h:1683
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
In kernel/sched/core.c (ffffffff8114b036)
Location: include/linux/sched.h:1591
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81188bc7)
Location: include/linux/sched.h:1591
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811d3dad)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81275fef)
Location: include/linux/sched.h:1591
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812adfcf)
Location: include/linux/sched.h:1591
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff815ac1a9)
Location: include/linux/sched.h:1591
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010133a84)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffff800010160650)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230808)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffff8000104453e0)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (c0383178)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (c03ad100)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/trace/trace_sched_wakeup.c (c046c8a4)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (c060a284)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (c00000000017ecb8)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (c0000000001b68d4)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002baf28)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (c00000000055ad1c)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffe0000e6354)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffe000104cce)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000189172)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffe0002db2ec)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
</details>
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
In kernel/sched/core.c (ffffffff810cd75b)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810f510f)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab1fa)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81371475)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810bbfdb)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810e52cf)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e503)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff81361f05)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810ccbbb)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810f230f)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a8fca)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff8136ef45)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
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
In kernel/sched/core.c (ffffffff810d55fb)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_switch
  - kernel/sched/core.c:trace_event_raw_event_sched_switch
```
```
In kernel/sched/debug.c (ffffffff810fd2ff)
Location: include/linux/sched.h:1399
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b6e0a)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
```
```
In fs/proc/array.c (ffffffff813828d5)
Location: include/linux/sched.h:1399
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:task_state
```
</details>
</li>
</ul>

## Differences
