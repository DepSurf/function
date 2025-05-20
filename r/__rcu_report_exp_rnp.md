# Function: <code>__rcu_report_exp_rnp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4f80)
Location: kernel/rcu/tree.c:3509
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb802)
Location: kernel/rcu/tree_exp.h:151
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f17e8)
Location: kernel/rcu/tree_exp.h:151
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2678)
Location: kernel/rcu/tree_exp.h:167
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc408)
Location: kernel/rcu/tree_exp.h:167
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811054e4)
Location: kernel/rcu/tree_exp.h:197
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110cbc)
Location: kernel/rcu/tree_exp.h:197
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff8111a72f)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff81126b3f)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134700)
Location: kernel/rcu/tree_exp.h:182
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff81134700-ffffffff811347c0: __rcu_report_exp_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811301a0)
Location: kernel/rcu/tree_exp.h:182
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff811301a0-ffffffff81130260: __rcu_report_exp_rnp (STB_LOCAL)
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
Location: kernel/rcu/tree_exp.h:182
Inline: True
Inline callers:
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:182
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81178290)
Location: kernel/rcu/tree_exp.h:182
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff81178290-ffffffff8117835f: __rcu_report_exp_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811afd10)
Location: kernel/rcu/tree_exp.h:184
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff811afd10-ffffffff811afddf: __rcu_report_exp_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c1d80)
Location: kernel/rcu/tree_exp.h:185
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff811c1d80-ffffffff811c1e4f: __rcu_report_exp_rnp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d4bd0)
Location: kernel/rcu/tree_exp.h:184
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff811d4bd0-ffffffff811d4c9f: __rcu_report_exp_rnp (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff80001018da28)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (c03da01c)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (c0000000001e6780)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffe000121656)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff8111f11f)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff81110b2f)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
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
In kernel/rcu/tree.c (ffffffff8111d00f)
Location: kernel/rcu/tree_exp.h:187
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rcu_report_exp_rnp(struct rcu_node *rnp, bool wake, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127af0)
Location: kernel/rcu/tree_exp.h:187
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcu_report_exp_cpu_mult
```
**Symbols:**

```
ffffffff81127af0-ffffffff81127ba4: __rcu_report_exp_rnp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<b>Flavor</b>
<ul>
</ul>
