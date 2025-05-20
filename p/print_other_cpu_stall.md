# Function: <code>print_other_cpu_stall</code>

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
Location: kernel/rcu/tree.c:1227
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
Location: kernel/rcu/tree.c:1323
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
Location: kernel/rcu/tree.c:1325
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
Location: kernel/rcu/tree.c:1422
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
Location: kernel/rcu/tree.c:1491
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
In kernel/rcu/tree.c (ffffffff811083bd)
Location: kernel/rcu/tree.c:1368
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
In kernel/rcu/tree.c (ffffffff8111391e)
Location: kernel/rcu/tree.c:1244
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
In kernel/rcu/tree.c (ffffffff8111d50b)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffff81129a38)
Location: kernel/rcu/tree_stall.h:354
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:454
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811355f0-ffffffff8113565b: print_other_cpu_stall (STB_LOCAL)
ffffffff8113907c-ffffffff811392a0: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:471
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff81130db0-ffffffff81130e1d: print_other_cpu_stall (STB_LOCAL)
ffffffff81be29ca-ffffffff81be2bf1: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:517
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff81131470-ffffffff81131621: print_other_cpu_stall (STB_LOCAL)
ffffffff81bd4901-ffffffff81bd4a0f: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:520
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff81153350-ffffffff811535be: print_other_cpu_stall (STB_LOCAL)
ffffffff81caee08-ffffffff81caefa0: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:557
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff8117bb90-ffffffff8117bdf2: print_other_cpu_stall (STB_LOCAL)
ffffffff81e5f939-ffffffff81e5fb52: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811b4820-ffffffff811b4d9e: print_other_cpu_stall (STB_LOCAL)
ffffffff8205a099-ffffffff8205a0cc: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:583
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811c5cf0-ffffffff811c626e: print_other_cpu_stall (STB_LOCAL)
ffffffff820d886b-ffffffff820d8898: print_other_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void print_other_cpu_stall(long unsigned int gp_seq, long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:590
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811d6190-ffffffff811d670e: print_other_cpu_stall (STB_LOCAL)
ffffffff821b3b56-ffffffff821b3b83: print_other_cpu_stall.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff80001019107c)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (c03decf0)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (c0000000001ec6c4)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffe00012451c)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffff81122018)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffff811146c0)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffff8111ff08)
Location: kernel/rcu/tree_stall.h:354
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
In kernel/rcu/tree.c (ffffffff8112c1ca)
Location: kernel/rcu/tree_stall.h:354
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
