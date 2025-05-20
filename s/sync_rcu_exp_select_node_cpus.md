# Function: <code>sync_rcu_exp_select_node_cpus</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811057b0)
Location: kernel/rcu/tree_exp.h:383
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811057b0-ffffffff81105ab3: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110ed0)
Location: kernel/rcu/tree_exp.h:343
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff81110ed0-ffffffff811111df: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111a8b0)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8111a8b0-ffffffff8111aba7: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81126cc0)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff81126cc0-ffffffff81126f94: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134950)
Location: kernel/rcu/tree_exp.h:337
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff81134950-ffffffff81134c40: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811303f0)
Location: kernel/rcu/tree_exp.h:337
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811303f0-ffffffff811306e0: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811309b0)
Location: kernel/rcu/tree_exp.h:337
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811309b0-ffffffff81130cd6: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811525c0)
Location: kernel/rcu/tree_exp.h:337
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811525c0-ffffffff811528e3: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117af86)
Location: kernel/rcu/tree_exp.h:471
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8117ad90-ffffffff8117adaa: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b5dc6)
Location: kernel/rcu/tree_exp.h:473
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811b5bc0-ffffffff811b5bda: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c6d46)
Location: kernel/rcu/tree_exp.h:474
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811c6b40-ffffffff811c6b5a: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d6fa6)
Location: kernel/rcu/tree_exp.h:473
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff811d6da0-ffffffff811d6dba: sync_rcu_exp_select_node_cpus (STB_LOCAL)
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
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f478)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffff80001018f478-ffff80001018f83c: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dae48)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
c03dae48-c03db184: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7590)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
c0000000001e7590-c0000000001e7990: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe00012190e)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffe00012190e-ffffffe000121b7a: sync_rcu_exp_select_node_cpus (STB_LOCAL)
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
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f2a0)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8111f2a0-ffffffff8111f574: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110d10)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff81110d10-ffffffff81110fe4: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d190)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff8111d190-ffffffff8111d464: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_rcu_exp_select_node_cpus(struct work_struct *wp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128060)
Location: kernel/rcu/tree_exp.h:332
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sync_rcu_exp_select_cpus
```
**Symbols:**

```
ffffffff81128060-ffffffff81128383: sync_rcu_exp_select_node_cpus (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
