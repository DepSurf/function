# Function: <code>rcu_report_exp_cpu_mult</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4f50)
Location: kernel/rcu/tree.c:3562
Inline: True
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:rcu_cpu_notify
```
**Symbols:**

```
ffffffff810e4f50-ffffffff810e502f: rcu_report_exp_cpu_mult.constprop.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb7d0)
Location: kernel/rcu/tree_exp.h:202
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff810eb7d0-ffffffff810eb8d1: rcu_report_exp_cpu_mult.constprop.79 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f17b0)
Location: kernel/rcu/tree_exp.h:202
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff810f17b0-ffffffff810f18a7: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2640)
Location: kernel/rcu/tree_exp.h:218
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff810f2640-ffffffff810f2708: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc3d0)
Location: kernel/rcu/tree_exp.h:218
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff810fc3d0-ffffffff810fc49b: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_state *rsp, struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811054a0)
Location: kernel/rcu/tree_exp.h:245
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff811054a0-ffffffff81105576: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110c80)
Location: kernel/rcu/tree_exp.h:244
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff81110c80-ffffffff81110d4a: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a6f0)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff8111a6f0-ffffffff8111a7c4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126b00)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff81126b00-ffffffff81126bd4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811347c0)
Location: kernel/rcu/tree_exp.h:230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811347c0-ffffffff811348a4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130260)
Location: kernel/rcu/tree_exp.h:230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff81130260-ffffffff81130347: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811307a0)
Location: kernel/rcu/tree_exp.h:230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff811307a0-ffffffff81130901: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81152360)
Location: kernel/rcu/tree_exp.h:230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
  - kernel/rcu/tree.c:rcu_softirq_qs
```
**Symbols:**

```
ffffffff81152360-ffffffff811524f9: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81179880)
Location: kernel/rcu/tree_exp.h:230
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_preempt_ctxt_queue
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff81179880-ffffffff811799bf: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b5300)
Location: kernel/rcu/tree_exp.h:232
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_preempt_ctxt_queue
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
```
**Symbols:**

```
ffffffff811b5300-ffffffff811b543f: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c6280)
Location: kernel/rcu/tree_exp.h:233
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_preempt_ctxt_queue
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
```
**Symbols:**

```
ffffffff811c6280-ffffffff811c63bf: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:232
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_preempt_ctxt_queue
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:__sync_rcu_exp_select_node_cpus
```
**Symbols:**

```
ffffffff811d6720-ffffffff811d68dd: rcu_report_exp_cpu_mult (STB_LOCAL)
ffffffff821b3b83-ffffffff821b3bd5: rcu_report_exp_cpu_mult.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018d9b8)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffff80001018d9b8-ffff80001018db78: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03d9fdc)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
c03d9fdc-c03da0fc: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6720)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_qs
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
c0000000001e6720-c0000000001e6918: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe00012161a)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
```
**Symbols:**

```
ffffffe00012161a-ffffffe00012171c: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f0e0)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff8111f0e0-ffffffff8111f1b4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110af0)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff81110af0-ffffffff81110bc4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cfd0)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff8111cfd0-ffffffff8111d0a4: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_report_exp_cpu_mult(struct rcu_node *rnp, long unsigned int mask, bool wake);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127bb0)
Location: kernel/rcu/tree_exp.h:234
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus
  - kernel/rcu/tree.c:rcu_report_dead
```
**Symbols:**

```
ffffffff81127bb0-ffffffff81127c09: rcu_report_exp_cpu_mult (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state *rsp</code>
</li>
<li>
<b>Param reordered. </b>
<code>rsp, rnp, mask, wake</code> ➡️ <code>rnp, mask, wake</code>
</li>
</ul>
</details>
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
