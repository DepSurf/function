# Function: <code>rcu_preempt_deferred_qs</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:1051
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:909
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:874
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:902
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:969
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:929
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81180766)
Location: kernel/rcu/tree_plugin.h:598
Inline: True
Inline callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff8117c860-ffffffff8117c889: rcu_preempt_deferred_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_preempt_deferred_qs(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811baf46)
Location: kernel/rcu/tree_plugin.h:598
Inline: True
Inline callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811b6bd0-ffffffff811b6c07: rcu_preempt_deferred_qs.part.0 (STB_LOCAL)
ffffffff811bae70-ffffffff811baeb4: rcu_preempt_deferred_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_preempt_deferred_qs(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cd886)
Location: kernel/rcu/tree_plugin.h:600
Inline: True
Inline callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811c7600-ffffffff811c7637: rcu_preempt_deferred_qs.part.0 (STB_LOCAL)
ffffffff811cd7b0-ffffffff811cd7f4: rcu_preempt_deferred_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_preempt_deferred_qs(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811e24c6)
Location: kernel/rcu/tree_plugin.h:600
Inline: True
Inline callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcutree_report_cpu_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_momentary_dyntick_idle
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811d7b20-ffffffff811d7b57: rcu_preempt_deferred_qs.part.0 (STB_LOCAL)
ffffffff811e23f0-ffffffff811e2434: rcu_preempt_deferred_qs (STB_GLOBAL)
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:886
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a770)
Location: kernel/rcu/tree_plugin.h:564
Inline: False
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_idle_enter
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff8112a770-ffffffff8112a7de: rcu_preempt_deferred_qs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>
