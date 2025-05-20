# Function: <code>rcu_preempt_ctxt_queue</code>

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
void rcu_preempt_ctxt_queue(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811799c0)
Location: kernel/rcu/tree_plugin.h:151
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff811799c0-ffffffff81179c5d: rcu_preempt_ctxt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_preempt_ctxt_queue(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b5450)
Location: kernel/rcu/tree_plugin.h:151
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff811b5450-ffffffff811b56ed: rcu_preempt_ctxt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_preempt_ctxt_queue(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c63d0)
Location: kernel/rcu/tree_plugin.h:151
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff811c63d0-ffffffff811c6677: rcu_preempt_ctxt_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_preempt_ctxt_queue(struct rcu_node *rnp, struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d7260)
Location: kernel/rcu/tree_plugin.h:151
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff811d7260-ffffffff811d7507: rcu_preempt_ctxt_queue (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112acd0)
Location: kernel/rcu/tree_plugin.h:130
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
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
