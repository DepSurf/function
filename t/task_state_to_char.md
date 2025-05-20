# Function: <code>task_state_to_char</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3aae)
Location: include/linux/sched.h:1261
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810d72d5)
Location: include/linux/sched.h:1261
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2e2c)
Location: include/linux/sched.h:1353
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810e1b88)
Location: include/linux/sched.h:1353
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc0de)
Location: include/linux/sched.h:1355
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810ec2d8)
Location: include/linux/sched.h:1355
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d44a2)
Location: include/linux/sched.h:1427
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810eff81)
Location: include/linux/sched.h:1427
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810deab2)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810fbddf)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6d1e)
Location: include/linux/sched.h:1462
Inline: True
```
```
In kernel/sched/debug.c (ffffffff8110652c)
Location: include/linux/sched.h:1462
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bdc537)
Location: include/linux/sched.h:1521
Inline: True
```
```
In kernel/sched/debug.c (ffffffff81104b7c)
Location: include/linux/sched.h:1521
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bce6de)
Location: include/linux/sched.h:1543
Inline: True
```
```
In kernel/sched/debug.c (ffffffff81106f12)
Location: include/linux/sched.h:1543
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810eec1f)
Location: include/linux/sched.h:1641
Inline: True
```
```
In kernel/sched/debug.c (ffffffff81124ec9)
Location: include/linux/sched.h:1641
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c9c77)
Location: include/linux/sched.h:1641
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
char task_state_to_char(struct task_struct *tsk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110ba9d)
Location: include/linux/sched.h:1666
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8113b510)
Location: include/linux/sched.h:1666
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fd84f)
Location: include/linux/sched.h:1666
Inline: True
```
**Symbols:**

```
ffffffff8113b510-ffffffff8113b579: task_state_to_char (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81131e5e)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8116aadc)
Location: include/linux/sched.h:1688
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8124501f)
Location: include/linux/sched.h:1688
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811400d6)
Location: include/linux/sched.h:1697
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117b1ec)
Location: include/linux/sched.h:1697
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125c0af)
Location: include/linux/sched.h:1697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114b036)
Location: include/linux/sched.h:1605
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff81188bc7)
Location: include/linux/sched.h:1605
Inline: True
```
```
In kernel/rcu/tree.c (ffffffff811d3dad)
Location: include/linux/sched.h:1605
Inline: True
Inline callers:
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:show_rcu_nocb_gp_state
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81275fef)
Location: include/linux/sched.h:1605
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013e504)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffff800010160650)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038e4e4)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (c03ad100)
Location: include/linux/sched.h:1421
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017e4d8)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (c0000000001b68d4)
Location: include/linux/sched.h:1421
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e61e2)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffe000104cce)
Location: include/linux/sched.h:1421
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8ca2)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f510f)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c76ad)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810e52cf)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4fe2)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810f230f)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0882)
Location: include/linux/sched.h:1421
Inline: True
```
```
In kernel/sched/debug.c (ffffffff810fd2ff)
Location: include/linux/sched.h:1421
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
