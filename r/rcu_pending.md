# Function: <code>rcu_pending</code>

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
In kernel/rcu/tree.c (ffffffff810e7edc)
Location: kernel/rcu/tree.c:3939
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
In kernel/rcu/tree.c (ffffffff810ee11c)
Location: kernel/rcu/tree.c:3533
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
In kernel/rcu/tree.c (ffffffff810f51fc)
Location: kernel/rcu/tree.c:3531
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
In kernel/rcu/tree.c (ffffffff810f5f7c)
Location: kernel/rcu/tree.c:3514
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
In kernel/rcu/tree.c (ffffffff810ffe1c)
Location: kernel/rcu/tree.c:3497
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
In kernel/rcu/tree.c (ffffffff8110813b)
Location: kernel/rcu/tree.c:3286
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
In kernel/rcu/tree.c (ffffffff81113656)
Location: kernel/rcu/tree.c:3021
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
In kernel/rcu/tree.c (ffffffff8111d25a)
Location: kernel/rcu/tree.c:2730
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
In kernel/rcu/tree.c (ffffffff8112975a)
Location: kernel/rcu/tree.c:2790
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
int rcu_pending(int user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81135850)
Location: kernel/rcu/tree.c:3485
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff81135850-ffffffff81135901: rcu_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcu_pending(int user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131000)
Location: kernel/rcu/tree.c:3795
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff81131000-ffffffff811310b7: rcu_pending (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff8113426e)
Location: kernel/rcu/tree.c:3901
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff8115686f)
Location: kernel/rcu/tree.c:3872
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff8117f8a5)
Location: kernel/rcu/tree.c:3968
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff811b9bc2)
Location: kernel/rcu/tree.c:3849
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/rcu/tree.c (ffffffff811cc412)
Location: kernel/rcu/tree.c:3849
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rcu_pending(int user);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:3921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff811d9130-ffffffff811d931a: rcu_pending (STB_LOCAL)
ffffffff821b3c98-ffffffff821b3cdd: rcu_pending.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff800010190d60)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (c03de978)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (c0000000001ec270)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (ffffffe00012432c)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (ffffffff81121d3a)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (ffffffff8111436a)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (ffffffff8111fc2a)
Location: kernel/rcu/tree.c:2790
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
In kernel/rcu/tree.c (ffffffff8112bdcf)
Location: kernel/rcu/tree.c:2790
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
</ul>
