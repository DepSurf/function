# Function: <code>ct_state_inc</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810e9f32)
Location: include/linux/context_tracking.h:128
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811ba316)
Location: include/linux/context_tracking.h:128
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/context_tracking.c (ffffffff820bff30)
Location: include/linux/context_tracking.h:128
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In lib/bug.c (ffffffff8201ec89)
Location: include/linux/context_tracking.h:128
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
In kernel/panic.c (ffffffff810f5b32)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811ccc65)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/context_tracking.c (ffffffff82141db0)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In lib/bug.c (ffffffff8209ec99)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
In kernel/panic.c (ffffffff810feee2)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811e1677)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
```
```
In kernel/context_tracking.c (ffffffff82224130)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_kernel_exit_state
```
```
In lib/bug.c (ffffffff82176c99)
Location: include/linux/context_tracking.h:129
Inline: True
Inline callers:
  - lib/bug.c:report_bug
  - lib/bug.c:report_bug
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
