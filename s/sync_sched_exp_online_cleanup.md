# Function: <code>sync_sched_exp_online_cleanup</code>

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
In kernel/rcu/tree.c (ffffffff810e5971)
Location: kernel/rcu/tree.c:3679
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_cpu_notify
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
In kernel/rcu/tree.c (ffffffff810ee925)
Location: kernel/rcu/tree_exp.h:322
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff810f5a15)
Location: kernel/rcu/tree_exp.h:322
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff810f67b8)
Location: kernel/rcu/tree_exp.h:340
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff81100780)
Location: kernel/rcu/tree_exp.h:340
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff811085d1)
Location: kernel/rcu/tree_exp.h:364
Inline: True
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
In kernel/rcu/tree.c (ffffffff81113ad4)
Location: kernel/rcu/tree_exp.h:791
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff8111d6bc)
Location: kernel/rcu/tree_exp.h:730
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff81129c5c)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_sched_exp_online_cleanup(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136c30)
Location: kernel/rcu/tree_exp.h:751
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff81136c30-ffffffff81136cd6: sync_sched_exp_online_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_sched_exp_online_cleanup(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132290)
Location: kernel/rcu/tree_exp.h:749
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
```
**Symbols:**

```
ffffffff81132290-ffffffff81132336: sync_sched_exp_online_cleanup (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff8113455c)
Location: kernel/rcu/tree_exp.h:750
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff81156bfd)
Location: kernel/rcu/tree_exp.h:751
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:783
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:788
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:791
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:794
Inline: True
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
In kernel/rcu/tree.c (ffff800010191828)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (c03df45c)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (c0000000001ece64)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffe000124b64)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff8112223c)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff8111490c)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (ffffffff8112012c)
Location: kernel/rcu/tree_exp.h:728
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_online_cpu
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_exp.h:672
Inline: True
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
