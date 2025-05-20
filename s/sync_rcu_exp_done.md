# Function: <code>sync_rcu_exp_done</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134550)
Location: kernel/rcu/tree_exp.h:150
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
In kernel/rcu/tree.c (ffffffff8112fff0)
Location: kernel/rcu/tree_exp.h:150
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
In kernel/rcu/tree.c (ffffffff81132254)
Location: kernel/rcu/tree_exp.h:150
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff81154634)
Location: kernel/rcu/tree_exp.h:150
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117c649)
Location: kernel/rcu/tree_exp.h:150
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
In kernel/rcu/tree.c (ffffffff811b66e4)
Location: kernel/rcu/tree_exp.h:152
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
In kernel/rcu/tree.c (ffffffff811c7114)
Location: kernel/rcu/tree_exp.h:153
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
In kernel/rcu/tree.c (ffffffff811d7634)
Location: kernel/rcu/tree_exp.h:153
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once
  - kernel/rcu/tree.c:__rcu_report_exp_rnp
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
