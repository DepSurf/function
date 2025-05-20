# Function: <code>trace_rcu_stall_warning</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_rcu_stall_warning(const char *rcuname, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8113233e)
Location: include/trace/events/rcu.h:443
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff811303f0-ffffffff8113042f: trace_rcu_stall_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_rcu_stall_warning(const char *rcuname, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8115471e)
Location: include/trace/events/rcu.h:444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff81151ee0-ffffffff81151f1c: trace_rcu_stall_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_rcu_stall_warning(const char *rcuname, const char *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117eabd)
Location: include/trace/events/rcu.h:444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
Direct callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
```
**Symbols:**

```
ffffffff8117a3a0-ffffffff8117a422: trace_rcu_stall_warning (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff811b3fde)
Location: include/trace/events/rcu.h:444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
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
In kernel/rcu/tree.c (ffffffff811cb418)
Location: include/trace/events/rcu.h:444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff811dd728)
Location: include/trace/events/rcu.h:444
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
