# Function: <code>sync_exp_reset_tree_hotplug</code>

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
In kernel/rcu/tree.c (ffffffff810e5188)
Location: kernel/rcu/tree.c:3409
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
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
In kernel/rcu/tree.c (ffffffff810eba22)
Location: kernel/rcu/tree_exp.h:54
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
In kernel/rcu/tree.c (ffffffff810f1c69)
Location: kernel/rcu/tree_exp.h:54
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff810f2a63)
Location: kernel/rcu/tree_exp.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff810fc80d)
Location: kernel/rcu/tree_exp.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff81105ac5)
Location: kernel/rcu/tree_exp.h:81
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff811111e5)
Location: kernel/rcu/tree_exp.h:81
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff8111abb5)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff81126fa5)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_exp_reset_tree_hotplug();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811337d0)
Location: kernel/rcu/tree_exp.h:73
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811337d0-ffffffff811338c8: sync_exp_reset_tree_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_exp_reset_tree_hotplug();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112ee70)
Location: kernel/rcu/tree_exp.h:73
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8112ee70-ffffffff8112ef68: sync_exp_reset_tree_hotplug (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff81130ce5)
Location: kernel/rcu/tree_exp.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff811528f5)
Location: kernel/rcu/tree_exp.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff8117adb5)
Location: kernel/rcu/tree_exp.h:73
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff811b5bf5)
Location: kernel/rcu/tree_exp.h:75
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff811c6b75)
Location: kernel/rcu/tree_exp.h:76
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff811d6dd5)
Location: kernel/rcu/tree_exp.h:76
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffff80001018f87c)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (c03db19c)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (c0000000001e79b8)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffe000121ba2)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff8111f585)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff81110ff5)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff8111d475)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
In kernel/rcu/tree.c (ffffffff81128395)
Location: kernel/rcu/tree_exp.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
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
