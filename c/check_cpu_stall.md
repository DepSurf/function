# Function: <code>check_cpu_stall</code>

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
In kernel/rcu/tree.c (ffffffff810e7f41)
Location: kernel/rcu/tree.c:1346
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff810ee167)
Location: kernel/rcu/tree.c:1455
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff810f5247)
Location: kernel/rcu/tree.c:1457
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff810f5fd6)
Location: kernel/rcu/tree.c:1556
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff810ffe76)
Location: kernel/rcu/tree.c:1628
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff811081c7)
Location: kernel/rcu/tree.c:1505
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff81113672)
Location: kernel/rcu/tree.c:1370
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
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
In kernel/rcu/tree.c (ffffffff8111d276)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff81129777)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135660)
Location: kernel/rcu/tree_stall.h:575
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_pending
```
**Symbols:**

```
ffffffff81135660-ffffffff81135849: check_cpu_stall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81130e20)
Location: kernel/rcu/tree_stall.h:591
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_pending
```
**Symbols:**

```
ffffffff81130e20-ffffffff81130ffa: check_cpu_stall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131630)
Location: kernel/rcu/tree_stall.h:646
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff81131630-ffffffff8113180a: check_cpu_stall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:649
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811535c0-ffffffff81153823: check_cpu_stall (STB_LOCAL)
ffffffff81caefa0-ffffffff81caefca: check_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:689
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff8117be00-ffffffff8117c06b: check_cpu_stall (STB_LOCAL)
ffffffff81e5fb52-ffffffff81e5fb7a: check_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:681
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811b5080-ffffffff811b52eb: check_cpu_stall (STB_LOCAL)
ffffffff8205a0e0-ffffffff8205a108: check_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:712
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811c9ad0-ffffffff811c9d3b: check_cpu_stall (STB_LOCAL)
ffffffff820d89ef-ffffffff820d8a17: check_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_cpu_stall(struct rcu_data *rdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:719
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_pending
```
**Symbols:**

```
ffffffff811d8e40-ffffffff811d9068: check_cpu_stall (STB_LOCAL)
ffffffff821b3c70-ffffffff821b3c98: check_cpu_stall.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff800010190d78)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (c03de99c)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (c0000000001ec284)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffe000124330)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff81121d57)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff81114387)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff8111fc47)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112bdec)
Location: kernel/rcu/tree_stall.h:477
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
