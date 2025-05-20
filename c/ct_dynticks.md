# Function: <code>ct_dynticks</code>

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
In kernel/rcu/tree.c (ffffffff811ba300)
Location: include/linux/context_tracking_state.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/context_tracking.c (ffffffff820c020c)
Location: include/linux/context_tracking_state.h:57
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
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
In kernel/rcu/tree.c (ffffffff811ccc4f)
Location: include/linux/context_tracking_state.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_starting
```
```
In kernel/context_tracking.c (ffffffff8214208c)
Location: include/linux/context_tracking_state.h:59
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
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
In kernel/rcu/tree.c (ffffffff811e1661)
Location: include/linux/context_tracking_state.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_report_cpu_starting
```
```
In kernel/context_tracking.c (ffffffff8222474c)
Location: include/linux/context_tracking_state.h:59
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
  - kernel/context_tracking.c:ct_nmi_exit
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
