# Function: <code>adjust_jiffies_till_sched_qs</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828ae6e5)
Location: kernel/rcu/tree.c:426
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff8111456b-ffffffff811145b5: adjust_jiffies_till_sched_qs.part.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828c718f)
Location: kernel/rcu/tree.c:435
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff8111e593-ffffffff8111e5dd: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828cf79d)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff8112ab13-ffffffff8112ab5d: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void adjust_jiffies_till_sched_qs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8113440a)
Location: kernel/rcu/tree.c:501
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81138e2e-ffffffff81138e78: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
ffffffff81133df0-ffffffff81133e13: adjust_jiffies_till_sched_qs (STB_LOCAL)
ffffffff81138e78-ffffffff81138e82: adjust_jiffies_till_sched_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void adjust_jiffies_till_sched_qs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112feaa)
Location: kernel/rcu/tree.c:515
Inline: True
Inline callers:
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81be2801-ffffffff81be284b: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
ffffffff8112f550-ffffffff8112f573: adjust_jiffies_till_sched_qs (STB_LOCAL)
ffffffff81be284b-ffffffff81be2855: adjust_jiffies_till_sched_qs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134be8)
Location: kernel/rcu/tree.c:521
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81bd47a6-ffffffff81bd47f0: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811573ba)
Location: kernel/rcu/tree.c:496
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81caeb67-ffffffff81caebb1: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81180517)
Location: kernel/rcu/tree.c:507
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81e5f233-ffffffff81e5f289: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void adjust_jiffies_till_sched_qs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b06e0)
Location: kernel/rcu/tree.c:438
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff811b06e0-ffffffff811b0758: adjust_jiffies_till_sched_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void adjust_jiffies_till_sched_qs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c26b0)
Location: kernel/rcu/tree.c:419
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff811c26b0-ffffffff811c2728: adjust_jiffies_till_sched_qs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void adjust_jiffies_till_sched_qs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d2c20)
Location: kernel/rcu/tree.c:420
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_init_geometry
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff811d2c20-ffffffff811d2c98: adjust_jiffies_till_sched_qs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffff800011446f78)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffff800010192b6c-ffff800010192bd4: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (c1521630)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
c03e0234-c03e0298: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (c00000000136c048)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
c0000000001edfb8-c0000000001ee044: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000008a22)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffe000125534-ffffffe000125594: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828b8495)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff811230f3-ffffffff8112313d: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828b07cb)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81115b3c-ffffffff81115b86: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828cb3d1)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff81120fe3-ffffffff8112102d: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828d07cb)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:param_set_next_fqs_jiffies
  - kernel/rcu/tree.c:param_set_first_fqs_jiffies
```
**Symbols:**

```
ffffffff8112d336-ffffffff8112d380: adjust_jiffies_till_sched_qs.part.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
