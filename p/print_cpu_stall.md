# Function: <code>print_cpu_stall</code>

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
In kernel/rcu/tree.c (ffffffff810e828b)
Location: kernel/rcu/tree.c:1304
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
In kernel/rcu/tree.c (ffffffff810ee505)
Location: kernel/rcu/tree.c:1406
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
In kernel/rcu/tree.c (ffffffff810f55e5)
Location: kernel/rcu/tree.c:1408
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
In kernel/rcu/tree.c (ffffffff810f634f)
Location: kernel/rcu/tree.c:1506
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
In kernel/rcu/tree.c (ffffffff811001fa)
Location: kernel/rcu/tree.c:1575
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
In kernel/rcu/tree.c (ffffffff81108493)
Location: kernel/rcu/tree.c:1452
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
In kernel/rcu/tree.c (ffffffff811138c4)
Location: kernel/rcu/tree.c:1316
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
In kernel/rcu/tree.c (ffffffff8111d33d)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffff8112983f)
Location: kernel/rcu/tree_stall.h:425
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
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:523
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff81134430-ffffffff81134496: print_cpu_stall (STB_LOCAL)
ffffffff81138ea2-ffffffff81138feb: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:539
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff8112fed0-ffffffff8112ff38: print_cpu_stall (STB_LOCAL)
ffffffff81be2881-ffffffff81be29ca: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
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
ffffffff81130620-ffffffff81130719: print_cpu_stall (STB_LOCAL)
ffffffff81bd4834-ffffffff81bd4901: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:593
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811521a0-ffffffff811522d8: print_cpu_stall (STB_LOCAL)
ffffffff81caecac-ffffffff81caed8e: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:630
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff8117ba30-ffffffff8117bb87: print_cpu_stall (STB_LOCAL)
ffffffff81e5f797-ffffffff81e5f939: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:625
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811b4db0-ffffffff811b5070: print_cpu_stall (STB_LOCAL)
ffffffff8205a0cc-ffffffff8205a0e0: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:656
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811c9800-ffffffff811c9ac0: print_cpu_stall (STB_LOCAL)
ffffffff820d89db-ffffffff820d89ef: print_cpu_stall.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void print_cpu_stall(long unsigned int gps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:663
Inline: False
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
```
**Symbols:**

```
ffffffff811d8b70-ffffffff811d8e30: print_cpu_stall (STB_LOCAL)
ffffffff821b3c5c-ffffffff821b3c70: print_cpu_stall.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff800010191110)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (c03dedac)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (c0000000001ec384)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffe00012440e)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffff81121e1f)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffff8111444f)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffff8111fd0f)
Location: kernel/rcu/tree_stall.h:425
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
In kernel/rcu/tree.c (ffffffff8112beb4)
Location: kernel/rcu/tree_stall.h:425
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
