# Function: <code>rcu_preempt_deferred_qs_irqrestore</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs_irqrestore(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117c530)
Location: kernel/rcu/tree_plugin.h:464
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
**Symbols:**

```
ffffffff8117c530-ffffffff8117c85a: rcu_preempt_deferred_qs_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs_irqrestore(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b65d0)
Location: kernel/rcu/tree_plugin.h:464
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
**Symbols:**

```
ffffffff811b65d0-ffffffff811b68f5: rcu_preempt_deferred_qs_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs_irqrestore(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c7000)
Location: kernel/rcu/tree_plugin.h:466
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
**Symbols:**

```
ffffffff811c7000-ffffffff811c7325: rcu_preempt_deferred_qs_irqrestore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs_irqrestore(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d7520)
Location: kernel/rcu/tree_plugin.h:466
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
```
**Symbols:**

```
ffffffff811d7520-ffffffff811d7845: rcu_preempt_deferred_qs_irqrestore (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_preempt_deferred_qs_irqrestore(struct task_struct *t, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129210)
Location: kernel/rcu/tree_plugin.h:425
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs
  - kernel/rcu/tree.c:__rcu_read_unlock
```
**Symbols:**

```
ffffffff81129210-ffffffff811294ac: rcu_preempt_deferred_qs_irqrestore (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Flavor</b>
<ul>
</ul>
